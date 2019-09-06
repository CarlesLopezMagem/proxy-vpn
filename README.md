# proxy-vpn

## Instal·lació

Ens baixem OpenVpn installer Server

```bash
curl -O https://raw.githubusercontent.com/Angristan/openvpn-install/master/openvpn-install.sh
chmod +x openvpn-install.sh
```

Executem l'instalador i instalem tots els parametres per defecte

```bash
./openvpn-install.sh
```

L'instal·Lador també et crearà un fitxer `.ovpn` per configurar el client. Afegeixes la vpn al teu client (per Mac he fet servir `Tunnelblick`).

Finalment crees el reverse proxy amb el docker-compose:

```bash
docker-compose up -d --build
```

## Links

- Tutorial (<https://www.youtube.com/watch?v=OXjrBvSYB9o/>)

- Instal·lador OpneVPN (<https://github.com/Angristan/OpenVPN-install/>)
