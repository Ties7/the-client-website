# Drop & Heal

Dit is een design van de onboarding pagina's voor de Drop & Heal website/webapp uitgewerkt tot html en css.



## Inhoudsopgave Readme

  * [Beschrijving](#beschrijving)
  * [Kenmerken](#kenmerken)
  * [Licentie](#licentie)

## Beschrijving

Hier staat de website: https://ties7.github.io/the-client-website/

Tot nu toe bestaat de onboarding uit 4 pagina's.

Dit is hoe het er op desktop uit ziet:

![Schermopname (7)](https://github.com/user-attachments/assets/d812afca-cf01-474d-9dcc-21f43f775f37)
![Schermopname (8)](https://github.com/user-attachments/assets/3eb01500-8576-47a4-a78f-d561a90a7e6d)
![Schermopname (9)](https://github.com/user-attachments/assets/a0e0c422-213f-47dc-8aed-e0adc65e1e40)
![Schermopname (10)](https://github.com/user-attachments/assets/7f8c9714-45e1-4cee-b9c3-1efd1b1e3642)

Dit is hoe het er op mobile uit ziet:

![image](https://github.com/user-attachments/assets/38477a3d-3ac6-4bac-a0e8-8645e0f2fcdf)
![image](https://github.com/user-attachments/assets/428b6a91-abb1-41fa-8b7a-e43d65144ab5)
![image](https://github.com/user-attachments/assets/96c7dfbc-356e-44d3-81a5-a6cc5d340ec8)
![image](https://github.com/user-attachments/assets/09b0daf0-d927-4ecd-8fa3-7bf8e9cc6955)



<!-- In de Beschrijving staat hoe je project er uit ziet, hoe het werkt en wat je er mee kan. -->
<!-- Voeg een mooie poster visual toe 📸 -->
<!-- Voeg een link toe naar Github Pages 🌐-->

## Kenmerken

De website is gebouwd met html en css.

### HTML
Op de ```<body>``` staat een regel code waardoor de pagina bij het laden een fade-in heeft.

```<body onload="document.body.style.opacity='1'">
```

### CSS
De css code op de body waardoor de pagina bij het laden een fade-in heeft.
```body {
    opacity: 0;
    transition: opacity 3s;
}
```

Ik heb gebruik gemaakt van @media, waardoor de website responsive is en bij een bepaalde grootte van het scherm de layout veranderd zodat het er op elk soort scherm mooi uit ziet.

```@media only screen and (max-width: 600px) {
    .task-header {
        margin-top: 8rem;
        height: 24rem;
    }

    .task-header > img {
        left: -8rem;
        transform: none;
    }

    .task-article {
        position: static;
        transform: none;
        padding-left: 1.3rem;
    }
}
```




## Licentie

This project is licensed under the terms of the [MIT license](./LICENSE).
