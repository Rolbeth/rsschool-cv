***
# Shamin Evgeniy
***
## Web Developer
***
### Contact Information

**Phone:** +7 926 660 0538

**E-mail:** x91.2008@gmail.com

**Telegram:** @Rolbeth

[Тескт ссылки 1](http://ya.ru "Описание 2")

[Тескт ссылки 2](http://ya.ru "Описание 2") 

***
### Briefly About Myself:

"Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum."


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
* C, C++, Java - lost skills
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
