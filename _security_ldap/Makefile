#####################################################################
### make
#####################################################################

all:

#####################################################################
### make init
#####################################################################

.PHONY: init
init: init-secret

.PHONY: init-secret
init-secret: \
	init-secret-_security_openldap

.PHONY: init-secret-_security_openldap
init-secret-_security_openldap:
	mkdir -p .secret/__envrc.d
	cp -rf $(HOME)/.danny/var/secret/security-ldap/__envrc.d/* .secret/__envrc.d/
