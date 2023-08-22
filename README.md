# Personal Website

Simple personal website built with Python and [Flask](http://flask.pocoo.org/).
The deploy is done with [Frozen-Flask](https://pythonhosted.org/Frozen-Flask/) and [Netlify](https://www.netlify.com/).


![Screen Shot 2023-08-22 at 3 00 36 PM](https://github.com/datatalking/2023_website/assets/11813209/b2018435-012a-4131-ab93-cb244c4d5284)


#### Development

If you install new packages, remember to update `requirements.txt`:

```sh
pip freeze > requirements.txt
```

#### Deployment

<a href="https://www.netlify.com">
  <img src="https://www.netlify.com/img/global/badges/netlify-dark.svg"/>
</a>

##### Netlify settings

* Build command: `python freeze.py`
* Publish directory: `build`

#### Notes

Read my [Medium article](https://medium.com/@francescaguiducci/how-to-build-a-simple-personal-website-with-python-flask-and-netlify-d800c97c283d) to find out about why I created this repo and other fun stuff.

#### Future
* this represents the final v1 of my portfolio blog
* v2 will be a three column layout and 7 sub pages for
* v2 Portfolio
* v2 Blog
* v2 Resources
* v2 Projects
* v2 CV
* v2 About
* v2 Search icon
