# url-shorteners
A collection of my url-shortener repos. Inspired by TodoMVC list and similar


These projects exist solely for me to evaluate various stacks, learn new tech with a common domain - url-shortener, just my variation on the popular http://todomvc.com/, but with url shortners apis.

All projects share the same requirements: 

### API format: 

  a) can create a redirect link, get it by id and get it by slug (see `example.http` file in each repo).
  
  Entity is ShortLink:

    - id
    - slug
    - destination

  b) can then got to redirect/some-slug and get redirected to the destination.

### System Requirements: 
  - can store a lot of links.
  - shortlinks are as short as possible.
  - following a shortlink is fast.
  - shortlink follower is resilient to load spikes.

| Language  | Framework  | DB    | ORM  | Containers  | GitHub Repo                                      |
|-----------|------------|-------|------|-------------|--------------------------------------------------|
|  C#       | .NET5      | MSSQL | EF   | Docker      |https://github.com/alanmynah/url-shortener-csharp |


