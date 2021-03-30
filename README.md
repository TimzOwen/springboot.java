# springboot.java

## Spring official documentations and README.md

#### Official site documentation

[Spring official documentation](https://spring.io/)

[Documentations and references](https://docs.spring.io/spring-framework/docs/5.0.14.RELEASE/spring-framework-reference/)

#### Software Requirements 

[STS-Spring Tool Suit](https://spring.io/tools)

[Java jdk 8 or 9 Recomended](https://www.oracle.com/java/technologies/javase/javase-jdk8-downloads.html)


### Design patterns 

    Dependency Injection:---> Classes and objects dending on others to work

__Loose Coupling__: Making objecrts not dependeable on anothers 

__tight coupling__: Making Classes ot objects that are dependable on one another.

    Ex:     class laptop{
                            HardDisk hd = new HitachiHD()     // Hardcording (bad pract)
                        }

#### Dependency Injection example

__Spring Containers__ -> Creates object for you for class injection

    Ex:  @Component
         class HitachiHD implements HardDrive{
             .........
         }

__Auto wiring and connection spring boot__:

    class Laptop{
        @autowired
        HardDrive hd;
    }

__Mock object__: used for testing classes without affecting the database for loosly couple software


### Marven Theory:

Maven United all java dependencies under one repository including the connections need for the program to run

depedencies are always located in __Pom.xml__ under the depencides section/ tags

