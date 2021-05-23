# Hello World!

```typescript
class Me extends SoftwareDeveloper {

    name: string = 'Francisco Ruiz';

    role: string = 'FullStack Web Developer';

    technologies: Array<string> = [
        'JavaScript and TypeScript',
        'React',
        'Node',
        'PHP',
        'Laravel',
        'MySQL',
        'Docker and docker-compose',
        'HTML and CSS'
    ];

    learning: Array<string> = [
        'Golang',
        'Testing',
        ...this.technologies
    ];

    wantToLearn: Array<string> = [
        'Deno',
        'How to be rich',
        'Rust'
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
