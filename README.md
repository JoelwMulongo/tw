Utilizes the Twitter API to fetch twitter posts, likes and lists. 

<img src="https://user-images.githubusercontent.com/75514748/202886500-7cc53a76-ba8e-4aed-b34e-83ed15d30df8.jpg">

```mermaid
graph LR
Request((Request))
Request --TwitterApi--> Twitter
Twitter((Twitter))
```
```mermaid
graph TD;

Twitter-->FetchedPost;
```
