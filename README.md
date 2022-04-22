[![Netlify Status](https://api.netlify.com/api/v1/badges/dcf3d5d0-a4a4-486f-bd9a-64b612392aad/deploy-status)](https://app.netlify.com/sites/brave-bell-c85a34/deploys)

## Todo

- [ ] Change Netlify build
- [ ] Add Publication

## Setup

### For Mac/Linux

``` bash
brew install ruby
gem install bundler jekyll
```

### For windows Install 
- Download Ruby+Devkit 2.6.9-1 [Link to Download](https://github.com/oneclick/rubyinstaller2/releases/download/RubyInstaller-2.6.9-1/rubyinstaller-devkit-2.6.9-1-x64.exe)
  
Clone this repository, then install the dependencies:


``` bash
bundle install
```

## Run

Run the local webserver with:

``` bash
bundle exec jekyll serve
```

## Contribute

### Add a new member
- Save pic in [images/teampic](images/teampic). 
- Image size must be less than 100 KB
- Image should be **square** of size (200 x 200). First crop your image to square shape then resize it to (200 x 200) size using https://www.iloveimg.com/resize-image 
- If photo is not available then use `researcher.png` placeholder image (already there).
This will help in maintaining loading speed and proper alignment of website images

Add details of members in [_data/lab_alumni.yml](_data/lab_alumni.yml) or [_data/lab_members.yml](_data/lab_members.yml). 

### Add a new publication
Publication will be automatically generate once you add bibtex.
Bibtex can be added in `.bib` file under [_pages/bibtex_publications.bib]

### Add news

News are stored as `.yml` file under [_data/news.yml](_data/news.yml).

An entry looks like the following:

```yaml
- date: 15 August 2021
  title: "Something great happened!"
```

### Edit template

We use [Bootstrap](https://getbootstrap.com/) for designing the website.
Feel free to modify either the [_pages](_pages/) or the
[_layouts](_layouts/) components.

# VCLab website template

This website is built with [Jekyll](https://jekyllrb.com/).
It is derived from the great template provided by the
[Allan Lab](https://www.allanlab.org/aboutwebsite.html), at Leiden University.
##### Template modified by Rohit Lal and Himanshu Patil