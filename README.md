This code helps when changing the color of the text when,

FULL Viedo ``` https://youtube.com/shorts/raurzPmEP0c?si=WWlj7_BfRc812rWd ```

# HTML
```
<div className="contant">
    <span>Hello Cucumberchik</span>
</div>
```
# CSS
```
.contant span {
    color: transperent;
    background-image: linear-gradient(90deg, rgba(176,91,81,1) 0%, rgba(135,42,172,1) 100%);
    background-clip: text;
    background-repeat: no-repeat;
    background-size: 0 100%;
    animation: scroll-reveel linear;
    animation-timeline: scroll();
}
@keyframes scroll-reveel {
    to{
        background-size: 100% 100%;
    }
}
```
