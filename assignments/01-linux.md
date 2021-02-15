# Linux Assignment
## Exercise File
* Create _wipcamp12_ directory inside your home directory
> cd ~
> mkdir wipcamp12

* Create programmer, website, network and ux-ui directory inside _wipcamp12_ directory
> cd wipcamp12  
> mkdir programmer website network ux-ui

* Create slide01.txt file inside your _wipcamp12_ directory
> touch slide01.txt  

* Copy slide01.txt to slide02.txt and slide03.txt inside _wipcamp12_ directory
> cp slide01.txt slide02.txt  
> cp slide01.txt slide03.txt

* Copy wipcamp12 directory to _wipcamp13_
> cd ..  
> cp -r wipcamp12 wipcamp13

* Delete slide03.txt inside _wipcamp13_
> rm wipcamp13/slide03.txt

* Move slide01.txt inside _wipcamp12_ to newslide.txt inside _wipcamp13_
> mv wipcamp12/slide01.txt wipcamp13/newslide.txt

* Delete _wipcamp12_ and _wipcamp13_
> rm -rf wipcamp12 wipcamp13