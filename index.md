## Marcus Ackland

```java
class Me extends Person {

    constructor() {
        super();
        
        this.name = 'Marcus Ackland';
        this.age = 25;
        this.nationality = 'Swedish';
        this.occupation' = 'MSc Student in Aerospace Engineering';
        this.graduationYear = calcGraduationYear(this.name);
        this.favoriteLanguage = getFavLanguage();
    
        getFavLanguage() {
            return 'Java, obviously!';
        }

        calcGraduationYear(name) {
            if( name.split(' ')[0] == 'Marcus') {
                return 2018;
            }
        }
    }   
}


```

## Projects

Coming soon..
