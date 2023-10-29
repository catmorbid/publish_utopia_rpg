# Kehitysympäristön asentaminen

## GitHub

- Luo tili https://github.com/signup
- Generoi [GitHub token](https://github.com/settings/tokens/new?scopes=repo,workflow) ja ota se talteen

## Obsidian.md
https://obsidian.md/

Tarvittavat plugarit:
- GitHub Publisher - mahdollistaa julkaisun tekemisen
	- konfiguroi GitHub:
	  username - oma käyttäjänimi
	  repository - `publish_utopia_rpg`
	  GitHub token - generoi token githubissa ja kopioi tähän
	  

Hyödylliset plugarit:
- Advanced Tables - taulukoiden editoinnin helpottamiseen
- Excel to Markdown Tables - kopioi taulukot google sheetsistä markdowniksi

## GitHub Desktop
https://desktop.github.com/

Lataa github desktop. Varmista, että GitHub-tili on ensin luotu.

# Basic Workflow
- Synkkaa työt -> GitHub Desktop: Fetch Origin / Pull
- Tee omat muutokset.
- Commitoi työt aina kun yksi sopivankokoinen muutos on tehty -> GitHubDesktop: changes / commit.
- Kun lopetat työt: PUSH

# Advanced Workflow
- Synkka työt
- Aloita muutosten teko -> GitHub Desktop Branch/New Branch (anna kuvaava nimi)
- Tee muutokset.
- Commit.
- Push.
- Kun olet valmis ja haluat hommat mainiin: Branch/Create Pull Request

# Publish Workflow
1. Katso, että GitHub Publisher on konfiguroitu oikein
2. Command Palette `CTRL+P` -> publish... valitse sopiva vaihtoehto.
3. Jos kaikki on mennyt oikein, niin jotain alkaa tapahtua ja hetken päästä tulee ilmoitus, että meni läpi.
4. Tarkista GitHubista menikö workflow läpi (vihreää valoa), ja pages-linkki pitäisi näyttää vihreää valoa myös. Tässä voi mennä muutamia minuutteja.
