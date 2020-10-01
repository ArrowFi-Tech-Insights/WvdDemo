<h1>Azure Active Directory Domain Services</h1>

<p>Tämä template luo Azure Active Directory Domain Services palvelun johon synkronoidaan käyttäjät ja ryhmät Azure AD:sta. Vanhat käyttäjät eivät synkronoidu ellei salasanaa resetoida. </p>
<p>HUOM!. Vaikka template ilmoittaa provisiointiprosession olevan valmis, ei domain ole vielä provisioitunut kokonaisuudessaan. Domainin tilan näet Azure AD Domain Servicesin alta "Overview" ja "Health" osiosta. Odota että domain on provisioitunut kokonaan ennen kuin menet eteenpäin</p>
<p>Kun domain on provisioitunut kokonaisuudessaan, tee domainiin uusi käyttäjä nimeltä domainjoiner. Kun käyttäjä on luotu kirjaudu käyttäjän väliaikaisella salasanalla myapps.microsoft.com portaaliin ja vaihda salasana kirjautumisen yhteydessä. Tätä salasanaa tarvitaan kun provisioidaan session host virtuaalikoneet ja liitetään ne domainiin.</p>

<a href="https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2FArrowFi-Tech-Insights%2FWvdDemo%2Fmaster%2FADDS%2Ftemplate.json" target="_blank">
    <img src="https://aka.ms/deploytoazurebutton"/>
