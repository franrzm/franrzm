# Hello World!

```typescript
class WhoAmI extends SoftwareDeveloper {

    name: string = 'Francisco Ruiz';

    role: string = 'FullStack Web Developer';

    technologies: Array<string> = [
        'JavaScript',
        'React',
        'Node',
        'PHP',
        'Laravel',
        'MySQL',
        'HTML',
        'CSS'
    ];

    learning: Array<string> = [
        'TypeScript',
        'Python',
        'Docker',
        ...this.technologies
    ];

    wantToLearn: Array<string> = [
        'Deno',
        'How to be rich',
        'Rust or Golang...'
    ];

    hobbiesAndInterests: Array<string> = [
        'Programming',
        'Nature',
        'Martial arts',
        'Photography'
    ];

    socialMediaUsername: string = '@franrzm';

    personalWebsite: string = 'https://www.franrzm.com/';

    workingAt: string = 'https://www.biyectiva.com/';

    constructor() {
        super();

        while(!this.dead) {
            this.eat();
            this.code();
            // this.sleep();
        }
    }
}
```
