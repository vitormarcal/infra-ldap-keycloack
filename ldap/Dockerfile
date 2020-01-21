FROM dwimberger/ldap-ad-it

EXPOSE 10389

COPY users.ldif /ldap/users.ldif

CMD ["java","-jar","ldap-server.jar", "users.ldif"]