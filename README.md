# [Anime-World V2](https://sandarvashakya.github.io/Anime-world-V2/)

Explore anime charcters and learn about them!! 

> Kaizoku Oni Orewa Naru!!


```
1. class wrapper:
        >covers the whole website

2. class page-1:
        >covers the first section i.e. background image,navigation logo
            -classes
                -header
                    >contains the entire navigation contents
                    >(logo,container-1)
                -logo
                    >contains anime world logo
                    >flex item of header
                -container-1
                    >contains navigation contents
                    >flex item of header
                    >(home,log-in,menu)
                -home
                    >flex item of container-1
                -log-in
                    >flex item of container-1
                -border
                    >the border below home and log-in
                -menu
                    >flex item of container-1
                -explore

3. class page-2:
        >the middle section i.e. the content and image
        >has id popular connected to home
        >is in the center i.e. margin auto
            -classes
                -container-2
                    >contains all the middle section
                    >(content)
                -content
                    >conatins a single card including image and article
                    >flex item of container-2
                    >(image,article)
                -image
                    >flex item of content
                    >image beside the article
                -article
                    >flex item of content
                    >article beside the image

4. class page-3:
        >covers the end section of the page i.e news and login form
            -classes
                -container-3
                    >covers the end section i.e. news and login form
                    >(news,sign-in)
                -news
                    >flex item of container-3
                    >contains the news section
                -sign-in
                    >flex item of container-3
                    >has id log-in connected to log-in
                    >(hex,form-row)
                -hex
                    >class for form
                    >covers all the elements like button text field etc.
                -form-row
                    >class for form
                    >covers single elements of form
```

