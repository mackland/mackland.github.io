## Marcus Ackland

```markdown
_class_ Me extends Person {

    constructor() {
        super();
        
        *this*.name = 'Marcus Ackland';
        *this*.age = 25;
        *this*.nationality = 'Swedish';
        'this.occupation' = 'MSc Student in Aerospace Engineering';
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

### Projects

Having trouble with Pages? Check out our [documentation](https://help.github.com/categories/github-pages-basics/) or [contact support](https://github.com/contact) and we’ll help you sort it out.
