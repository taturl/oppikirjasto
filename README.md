# Oppikirjasto

Emmekö voisi tehdä peruskoulun opetussuunnitelmaan perustuvat oppikirjat yhdessä, ja niin että kaikki saisivat lukea niitä vapaasti.

[Oppikirjasto.fi](oppikirjasto.fi) on uusi, avoin, maksuton ja kattava digitaalinen oppimateriaalikirjasto yläkoulun oppilaille Suomessa. Tekoälyn avulla generoidut oppikirjat kattavat koko yläasteen opetussuunnitelman kaikissa aineissa. Tavoitteemme on tarjota kaikille Suomen koululaisille parhaimmat mahdolliset opetusmateriaalit ja näin tehdä oppimisesta tasavertaisempaa.

## Miten voit osallistua?

Etsimme opettajia, opiskelijoita ja kaikkia opetuksesta kiinnostuneita osallistumaan yhteisön rakentamiseen ja avoimien oppimateriaalien kehittämiseen. Voit auttaa monin eri tavoin:

### 1. Kirjojen tarkistus ja laadun parantaminen
- Anna palautetta: Lue [oppikirjojamme](oppikirjasto.fi) ja anna palautetta mahdollisista virheistä tai parannuskohteista.
- Ehdota muutoksia: Voit ehdottaa muutoksia ja parannuksia suoraan tähän Github-säilytyspaikkaan, esimerkiksi avaamalla [uuden keskustelun](https://github.com/oppikirjasto/oppikirjasto/issues).

### 2. Sisällöntuotanto ja päivitys
- Kirjoita uusia lukuja: Voit kirjoittaa uusia lukuja tai osioita oppikirjoihin.
- Päivitä olemassa olevia: Päivitä ja laajenna jo olemassa olevaa sisältöä.

### 3. Käytännön apu
- Tekninen tuki: Osallistu tekniseen kehitykseen ja paranna sivuston käytettävyyttä.
- Markkinointi ja viestintä: Levitä sanaa projektistamme ja tuo lisää osallistujia mukaan.

### Miten aloittaa?

1. Luo käyttäjätili GitHub-palveluun, jotta voit osallistua keskusteluun ja seurata projektin edistymistä.
2. Tutustu ohjeisiin: Lue projektin ohjeet ja säännöt, jotka löydät myös Githubista.
3. Aloita osallistuminen: Valitse sinua kiinnostava osa-alue ja ala osallistumaan.

### Liity yhteisöömme

Tehdään yhdessä oppimisesta parempaa ja tasavertaisempaa kaikille Suomen koululaisille. Liity projektiimme ja osallistu uuden, avoimen ja ilmaisen oppikirjaston rakentamiseen!

### How to develop and run locally

- Requirements: Git, Node and Npm
- clone repository from cmd / terminal with command `git clone https://github.com/oppikirjasto/oppikirjasto.git`
- from command line change directory to the new directory with `cd oppikirjasto`
- run `npm install` to install dependencies
- run `npm run dev` to start local development server at [localhost:4321](localhost:4321) 

All commands are run from the root of the project, from a terminal:

| Command               | Action                                             |
| :-------------------- | :------------------------------------------------- |
| `npm install`         | Installs dependencies                              |
| `npm run dev`         | Starts local dev server at `localhost:4321`        |
| `npm run build`       | Build your production site to `./dist/`            |
| `npm run preview`     | Preview your build locally, before deploying       |
| `npm run format`      | Format codes with Prettier                         |
| `npm run lint:eslint` | Run Eslint                                         |
| `npm run astro ...`   | Run CLI commands like `astro add`, `astro preview` |

## Acknowledgements

Website template was created by [onWidget](https://onwidget.com) and maintained by a community of [contributors](https://github.com/onwidget/astrowind/graphs/contributors).

## License

**Oppikirjasto** is licensed under the MIT license — see the [LICENSE](./LICENSE.md) file for details.
