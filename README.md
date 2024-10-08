# :lock::door: [pfsense Captive Portal](https://doc.pfsense.org/index.php/Captive_Portal)
Modelos de páginas de login para captive portal no pfSense !

<p align="center">
  <img src="https://github.com/AlanMartines/pfSense-Captive-Portal/blob/main/screens/auth-login-password.png" alt="screenshot image of desktop" width="720px" />
</p>
<p align="center">
  <img src="https://github.com/AlanMartines/pfSense-Captive-Portal/blob/main/screens/auth-voucher.png" alt="screenshot image of desktop" width="720px" />
</p>
<p align="center">
  <img src="https://github.com/AlanMartines/pfSense-Captive-Portal/blob/main/screens/auth-login-password-voucher.png" alt="screenshot image of desktop" width="720px" />
</p>
<p align="center">
  <img src="https://github.com/AlanMartines/pfSense-Captive-Portal/blob/main/screens/termodeuso.png" alt="screenshot image of desktop" width="720px" />
</p>

Validado na versão do [pfsense 2.7.0](https://www.pfsense.org/download/).
As páginas do portal utilizam as variáveis `$PORTAL_ACTION$`, `$PORTAL_REDIRURL$`, `$PORTAL_ZONE$` e `$PORTAL_MESSAGE$` para obter dados do backend do firewall. As solicitações de autenticação são enviadas ao firewall por meio de requisições POST, garantindo uma integração eficaz entre a interface do portal e o sistema de autenticação do pfSense.

As páginas de login são:
- **Totalmente responsivas**
- **Compatíveis com todos os navegadores modernos**

Todas as páginas têm campos de entrada de Usuário/Senha escritos em HTML5 e CSS inline (na tag `head`):

- :arrow_right: **Login Page**
- :arrow_left: **Logout Page** com mensagem de logout
- :x: **Error Page** com mensagem de erro

Essa separação é fornecida e necessária pelo backend do pfSense, qualquer pessoa familiarizada com o portal cativo e o pfSense saberá disso. Fique à vontade para levantar questões se não estiver confortável com essa solução ou se houver algo que eu possa melhorar.

## :earth_africa: Suporte dos navegadores

| [<img src="https://raw.githubusercontent.com/alrra/browser-logos/master/src/edge/edge_48x48.png" alt="IE / Edge" width="24px" height="24px" />](http://godban.github.io/browsers-support-badges/)<br>IE / Edge | [<img src="https://raw.githubusercontent.com/alrra/browser-logos/master/src/firefox/firefox_48x48.png" alt="Firefox" width="24px" height="24px" />](http://godban.github.io/browsers-support-badges/)<br>Firefox | [<img src="https://raw.githubusercontent.com/alrra/browser-logos/master/src/chrome/chrome_48x48.png" alt="Chrome" width="24px" height="24px" />](http://godban.github.io/browsers-support-badges/)<br>Chrome | [<img src="https://raw.githubusercontent.com/alrra/browser-logos/master/src/safari/safari_48x48.png" alt="Safari" width="24px" height="24px" />](http://godban.github.io/browsers-support-badges/)<br>Safari | [<img src="https://raw.githubusercontent.com/alrra/browser-logos/master/src/safari-ios/safari-ios_48x48.png" alt="iOS Safari" width="24px" height="24px" />](http://godban.github.io/browsers-support-badges/)<br>iOS Safari | [<img src="https://raw.githubusercontent.com/alrra/browser-logos/master/src/samsung-internet/samsung-internet_48x48.png" alt="Samsung" width="24px" height="24px" />](http://godban.github.io/browsers-support-badges/)<br>Samsung | [<img src="https://raw.githubusercontent.com/alrra/browser-logos/master/src/opera/opera_48x48.png" alt="Opera" width="24px" height="24px" />](http://godban.github.io/browsers-support-badges/)<br>Opera |
| --------- | --------- | --------- | --------- | --------- | --------- | --------- |
| IE9, IE10, IE11, Edge| last versions| last versions| last versions| last versions| last versions| last versions

## :link: Uma lista de links úteis

- [Official Pfsense Captive Portal Documentation](https://doc.pfsense.org/index.php/Captive_Portal)
- [Official Pfsense Captive Portal Voucher Documentation](https://doc.pfsense.org/index.php/Captive_Portal_Vouchers)
