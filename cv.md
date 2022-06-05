***
# Shamin Evgeniy
***
## Web Developer
***
### Contact Information

**Phone:** +7 926 660 0538  
**E-mail:** x91.2008@gmail.com  
**Telegram:** @Rolbeth  
**GitHub:** https://github.com/Rolbeth/rsschool-cv  
**Discord:** Evgeniy#7408  

***
### Briefly About Myself:

I want to test myself on RSSchool courses.

***
### Skills and Proficiency:
* HTML5, CSS3
* JavaScript Basics
* Git
    + GitHub
    + Bitbucket
* VS Code, 
* Sql
    + MySql
    + Postgresql
* Php
* Golang
* Limux , Debian, Ubuntu 
* Apache , Nginx, Caady

***
### Code example:
```
func indexpage(c *fiber.Ctx) error {
	if GetSesAuth(SesStore, c) {
		return c.Redirect("/login/")
	}

	sess, _ := SesStore.Get(c)

	// Render index within layouts/main
	return c.Render("index", fiber.Map{
		"Title":    "Main Page",
		"UserName": sess.Get("Name"),
		"menuid":   1,
	}, "layouts/main")
}
```
### Education
* National Research University "Moscow Power Engineering Institute" , Nuclear power engineer
* Tomsk State University , Web Developer
* Courses:
    + Netology , Sql basic (Postgresql)

### Languages:
* Russian - Native
* English - A1