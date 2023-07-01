# utilities-invoices

<li>Concatenar campos</li>

```Visual basic
 =CONCAT(H8107,SUSTITUIR(I8107,"'",""))
```

## Obtener el keypem del .cer y .key  sat
código en openssl
<li>archivo .key</li>

```Bash
 openssl pkcs8 -inform DER -in Claveprivada_FIE.key -out Claveprivada_FIE.key.pem
```
<li>archivo .cer</li>

```Bash
openssl x509 -inform der -in 01111239.cer -pubkey -noout > certificate_publickey.pem
```