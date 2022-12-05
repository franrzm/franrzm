# Hello World!

```typescript
class FranciscoRuiz extends SoftwareDeveloper {
    as: Role = 'Tech Lead - Backend Developer';

    at: CompanyWebsite = 'https://widitrade.com/';

    moreAboutMe: PersonalWebsite = 'https://www.franrzm.com/';

    aka: SocialMediaUsername = '@franrzm';

    skills: Skills[] = [
        'SOLID principles and Clean Architectures',
        'Testing',
        'TypeScript',
        'Node',
        'PHP',
        'Laravel',
        'SQL',
        'Docker',
        'React and Vue'
    ];

    learning: Skills[] = [
        ...this.skills,
        'Golang'
    ];

    wantToLearn: Skills[] = [
        'How to be rich',
        'Rust'
    ];

    thingsILike: HobbiesAndInterests[] = [
        'Programming',
        'Nature',
        'Martial arts'
    ];

    newDay(): void {
        if(this.isDead) {
            return;
        }

        this.eat();
        this.code();
        // this.sleep();
    }
}
```
