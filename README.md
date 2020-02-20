tarteaucitron.js
================
Comply to the european cookie law is simple with the french *tarte au citron*.

# CustomText
 var tarteaucitronCustomText = {
        "alertBigPrivacy": "<div class='disclaimerTac'><h2 class='titleTac'>Grenoble-alpes métropole respecte votre vie privée</h2><h4 class='subTitleTac'>Nous utilisons des cookies pour améliorer votre navigation sur notre site et réaliser des statistiques anonymes. En cliquant sur &#34;J'accepte&#34;, vous nous donnez votre consentement pour les collecter.</h4> </div>",
        "denyAllLink": "Je refuse",
        "denyAll": "Interdire tous les cookies",
        "acceptAll": "J'accepte",
        "personalize": "Je sélectionne les cookies",
        "allowAll": "J'accepte tout",
        "disclaimer": "Ce site utilise des services qui collectent des cookies pour améliorer votre navigation et réaliser des statistiques, seulement si vous donnez votre accord. <br/> Vous pouvez accepter tous les cookies, sélectionner ci-dessous ceux que vous acceptez, ou tous les refuser.",
        "analytic":{
            "title": "Mesure d'audience",
            "details": "Les services de mesure d'audience permettent de générer des statistiques de fréquentation utiles à l'amélioration du site."
        }
    };
    
  # Init
   tarteaucitron.init({
        "privacyUrl": "",

        "hashtag": "#tarteaucitron",
        "cookieName": "tartaucitron",

        "orientation": "bottom",
        "showAlertSmall": false,
        "cookieslist": false,

        "adblocker": false,
        "AcceptAllCta": true,
        "highPrivacy": true,
        "handleBrowserDNTRequest": false,

        "removeCredit": true,
        "moreInfoLink": true,
        "useExternalCss": false,
        "freeConsent" : ['matomo']
    });
