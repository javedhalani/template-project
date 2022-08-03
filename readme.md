# Commands

## 2. Creating a template project

To create an archetype we have to use the following goal:

```
mvn archetype:create-from-project
```

Read [Create from project](https://maven.apache.org/archetype/maven-archetype-plugin/create-from-project-mojo.html) 
to know more.

Ensure that you have a `./settings` file at the location `${user.home}/.m2/` because maven uses this file to configure
archetype.



