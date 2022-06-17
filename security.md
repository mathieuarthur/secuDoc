# Security

- ## Global Security

		The project will need to be an E2EE one.
		
		All data are sensitive and need to be crypted since we collect it to the end.
		
		All documentation need to be crypted.
		
		Password need to be crypted.
		
		We would need to establish GDPR rules to make our users known which data we store and why.
		
- ## Password encryption

		All password will be need to be encrypted, if we use web interface using javascript we will need to encrypt it with bcrypt.
		
		All password must match this requirements:
		
		8 Characters min
		1 UpperCase letter min
		1 LowerCase letter min
		1 Number min
		1 special characters min

- ## E2EE method

		We should use an E2EE philosophy to secure all our data.
		
		So we will need to crypt any data we collect before sending it anywhere.
		
		Also we could force team member to talk on an irc using pgp method.

- ## Documentation

		All documentation should be store and share on skiff, an E2EE page storage like notion.

- ## Encryption method

		We could choose between AES or RSA encryption since both are still strong.
		
		RSA could be better but more complex to deploy.

- ## AES vs RSA

AES : 

![](../Downloads/rrss_01.png)

RSA :
![](../Downloads/how-rsa-works.png)