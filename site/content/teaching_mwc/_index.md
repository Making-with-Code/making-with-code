---
title: Teaching MwC
weight: 20
bookCollapseSection: true

---

# Teaching Making with Code

This site contains the curricula for *Making with Code* in the form we have used it. However, we encourage you to explore the resources, remake, and restructure them to meet your needs.

Our goal is for teaching *MwC* and implementing in your school to be a seamless setup process. 

---

## Repositories

💻 **All code is publicly available at [github.com/Making-with-Code](https://github.com/Making-with-Code).** We reccomend creating a new Github organization and forking the repositories as needed. 

If students are able to use Git and have Github accounts, you can create personalized repositories for each students under the organization. You can learn more about this process in [courseware](courseware)


{{< expand "Setup Steps" >}}

> **We typicall include the following in each lab or project in a seciton labeled 'Setup'.**

---

{{< code-action "Let's start by cloning the repository" >}} in your `cs10\unit00_networking` folder.  Be sure to change `yourgithubusername` to your actual Github username.

```shell
cd ~/desktop/making_with_code/cs10/unit00_networking
git clone https://github.com/the-isf-academy/lab_ballpit_yourgithubusername
cd lab_ballpit_yourgithubusername
```


{{< code-action "Enter the Poetry Shell." >}} 
```shell
poetry shell
```

{{< /expand  >}}

---

## Website 

This site is built using [Hugo](https://gohugo.io/) and can be hosted for no cost using Github pages. 

💻 **The site repoistory can be found at [github.com/Making-with-Code/making-with-code](https://github.com/Making-with-Code/making-with-code).** We encourage teachers to fork the site and customize to their community. 

There are currently two impplementation of thsi curriclum:
- [High School Computer Science in Hong Kong - ISF Academy](https://the-isf-academy.github.io/making-with-code/).
- [Teacher Preparation Program - SUNY Buffalo](https://makingwithcode.org/)

