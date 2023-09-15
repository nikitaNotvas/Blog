ZE NOT FUNNY BLOG WILL BE ABOUT MY NOT FUNNY ADVENTURE IN TA ZA CODING.
Here you will see new and not new things which I have learned and used in coding.
Some times I will post something about games I have recantly played for example: 

 Star Citizen is the game I recantly started plaing and got into mining with my vehicle like in picture ![in game mining with transport ](/assets/miningwithroc.jpeg)


# most recant post
<ul>
{% for post in site.posts %}    
    <li>
        <a href="{{ post.url}}">{{post.title }}</a>
    </li>
{%endfor %}

</ul>