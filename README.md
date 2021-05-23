<h1 align="center">
<img src="https://raw.githubusercontent.com/OldModz95-YTB/OldModz95-YTB/main/hi.gif" height="32" />
OldModz95
<img src="https://raw.githubusercontent.com/OldModz95-YTB/OldModz95-YTB/main/hi.gif" height="32" />
</h1>
<p align="center">
  <a href="https://discord.gg/3t2568W"><img src="https://discordapp.com/api/guilds/465584363489198091/widget.png?style=banner2" alt="Discord server"></a>
</p>
<p align="center">
  <a href="https://discord.gg/M3sTyHtcK4"><img src="https://discordapp.com/api/guilds/705278191404843051/widget.png?style=banner2" alt="Discord server"></a>
</p>

<br>

### Design Auth.gg New Version
<br>

## Installation
<br>
<br>

# Require
<br>

```
Launch file SLN


-PROGRAM.CS
OnProgramStart.Initialize("Login Authgg", "AID", "SECRET APP", "1.0");

```
<br>
<br>

# Require
<br>

[Visual Studio 2019](https://visualstudio.microsoft.com/fr/vs/community/)

<br>

# Information

```
version= v4.0
sku= .NETFramework,Version=v4.7.2
```

<br>
<br>
<br>
<br>

# Doc Code FR

```
////////////////////////////
Ajouter dans le program.cs
////////////////////////////


OnProgramStart.Initialize("Nom du logiciel", "AID DE VOTRE COMPTE", "KEY SECRET", "1.0");



//////////////////////////////////
Bouton ou fonctionnalité login
/////////////////////////////////


if (API.Login(pnlogin.Text, pnpass.Text))
            {
                timer2.Start();
                succeslogin.SHowDialog("Login Success !");
            }
            else
            {
                //Never
            }





///////////////////////////////////
Bouton ou fonctionnalité register
//////////////////////////////////


if (API.Register(reuser.Text, remail.Text, repass.Text, rekey.Text))
            {
                succeslogin.SHowDialog("Success Register !");
                panellogin.BringToFront();
                guna2Transition1.Show(panellogin);
            }




////////////////////////////
Fonctionnalié pour entrée
////////////////////////////


if (e.KeyCode == Keys.Enter)
            {
                register.PerformClick();
                e.Handled = true;
            }







/////////////////////////////////////////////////////////////////////////////////
Fonctionnalié pour reduire l'opacité de la form et ajouter une guna2Transition1
/////////////////////////////////////////////////////////////////////////////////






bunifuFormFadeTransition1.ShowAsyc(this);
            if (this.Opacity > 0)
            {
                this.Opacity -= 0.1;
            }





/////////////////////////////////////////////////////////
Information de l'utilisateur et abonnement
////////////////////////////////////////////////////////


label1.Text = "Username: " + User.Username;
label2.Text = "Email: " + User.Email;
label3.Text = "User Variable: " + User.UserVariable;
label4.Text = "HWID: " + User.HWID;
label5.Text = "IP: " + User.IP;
label6.Text = "Rank: " + User.Rank;
label7.Text = "Expiry: " + User.Expiry;
label8.Text = "Last Login: " + User.LastLogin;
label9.Text = "Register Date: " + User.RegisterDate;
pnlogin.Text = User.Username;





//////////////////////////
Valid License
//////////////////////////


if (API.ExtendSubscription(pnlogin.Text, passapi.Text, apiadd.Text))
            {
                Messagebox.Show("License Valid !");
                API.Log(pnlogin.Text, "Extend Subscription");
            }
            else
            {

            }




/////////////////
Login Infos User
///////////////////



if (API.Login(pnlogin.Text, conlogin.Text))
            {
                passapi.Text = conlogin.Text;
                panelpass.Visible = false;
                panelinfos.Visible = true;
                succeslogin.SHowDialog("Password Correct !");
            }
            else
            {

            }







///////////////
Refresh Infos
///////////////


if (API.Login(pnlogin.Text, passapi.Text))
            {
                timer2.Start();
                Messagebox.Show("Refresh All Information !");
            }
            else
            {
                
            }
```

<br>
<br>
<br>
<br>
<br>
<br>

## Picture

<br>
<img src="https://i.imgur.com/nJXRqXy.png">
<br>
<img src="https://i.imgur.com/fZ85QkI.png">
<br>


## 📞 Contact me

[Discord](https://www.discord.gg/3t2568W)
[Twitter](https://twitter.com/oldmodz95)
<br>
[YouTube (Server Private)](https://exotique.fr2.quickconnect.to/?launchApp=SYNO.SDS.VideoStation.AppInstance#!libOldModz95/N4IgNglgRgTghjAniAXCAFgewLYFMD6AbhACa6YC0A7CADQgDGcALrgOaZKohxhh0gADnDa5UARgC+QA)
<p>Username: ytb <br>
Password: oldmodz95</p>

<br />

## 🔧 Technologies & Tools


###### Version control system

![Git](https://img.shields.io/badge/-Git-000000?style=flat&logo=Git&logoColor=F05032)

###### License

![License](https://img.shields.io/github/license/ProtonD/Design-Auth.gg-New-Version)
```
Apache License
Version 2.0, January 2004
http://www.apache.org/licenses/
```

###### Operating systems

![Windows](https://img.shields.io/badge/-Windows-000000?style=flat&logo=Windows&logoColor=FCC624)


## &#x1f4c8; GitHub Stats

<a href="https://github.com/OldModz95-YTB">
  <img align="center" src="https://github-readme-stats.vercel.app/api/top-langs/?username=OldModz95-YTB&hide=java,html&title_color=ffffff&text_color=c9cacc&icon_color=2bbc8a&bg_color=1d1f21" />
</>
<a href="https://github.com/OldModz95-YTB">
  <img align="center" src="https://github-readme-stats.vercel.app/api?username=OldModz95-YTB&show_icons=true&line_height=27&count_private=true&title_color=ffffff&text_color=c9cacc&icon_color=ffff00&bg_color=1d1f21" alt="Crypt0's GitHub Stats" />
</a>

<p align="left"> <img src="https://komarev.com/ghpvc/?username=OldModz95-YTB" alt="OldModz95-YTB" /> </p>
