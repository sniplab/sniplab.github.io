动画实例网站
https://ouraring.com/
https://sun-earth.com/
https://www.taniarascia.com/notes/



https://www.framer.com/pricing
https://gsap.com/

https://v-gsap-nuxt.vercel.app/



SVG路径
https://yqnn.github.io/svg-path-editor/


swiper
https://swiperjs.com/react#controller


网站导航

https://www.uisdc.com/
Array.from(document.querySelectorAll('.part-cat-block')).map(a => {
    return {
        name: a.querySelector('h2').innerText.trim(),
        child: Array.from(a.querySelectorAll('.part-item-website')).map(aa => {
            return {
                href: aa.querySelector('a').href.trim(),
                title:  aa.querySelector('h3').innerText.trim(),
                img: aa.querySelector('img')?.src.trim(),
                desc: aa.querySelector('.item-desc')?.innerText.trim(),
            }
        })
    }
})


https://codernav.com/
