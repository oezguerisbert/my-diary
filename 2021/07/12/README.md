# Monday 12th July 2021

## Morning

I woke up in the morning and was reading emails and some new tech-new like RunJs. I also worked on my blog project, doing the backend. First version was developed and working, so I decided ot make it more generic and less complicated. I realized that I'm not thaaat good at TypeScript and the underlying implementation of the logic I wanted. I need to learn more about how to extract specific keys from a Class and use that for a search algorithm. Example (pseudo-code):

```typescript
class BasicEntity {
  public id: string = uuid.v4();

  public static find = <T extends BasicEntity>(criterias: SearchCriteria<T>) => { 
    // code
  }
}
class Post extends BasicEntity {
  public content: string = "";

  constructor(content:string) {
    this.content = content;
  }

}
```

the `SearchCriteria` type is important, I want it to be able to use `id:string` and `content:string` as a search criteria. but I don't want additional stuff such as the `symbol` of the class in there.

## Afternoon

After some research I didnt manage to make it work, so I let it be for now the state as it is.

## Night

I was rewarding myself with playing some games and watching a lot of naruto episodes. I enjoyed the evening quite well.
