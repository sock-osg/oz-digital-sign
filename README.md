oz-digital-sign
===============

Ejemplo de aplicacion swing firmada con plugin de maven

Creacion de jks

keytool -genkey -alias 'OZ-Cert' -keyalg RSA -sigalg SHA1withRSA -keypass '0r817#L=Z3rO' -storepass '5t0r3P#$wD' -keystore OZ.jks -dname "CN=Orbital Zero, OU=PMO, O=ORBITAL_ZERO, L=MEXICO, S=DF, C=MX"

