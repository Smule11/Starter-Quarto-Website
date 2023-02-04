# Starter-Quarto-Website

### What is Quarto?

Quarto is the most recent website creation tool, but has risen to become one of the most popular, in large part due to the reputation of the team making it. It is a website template tool, so you write in markdown (with a YAML header) and then you make Quarto render your markdown files into the website's HTML.

All Quarto does is turn your Markdown files into HTML files, the format of which can be tweaked by the optional associated YAML header, telling Quarto how to decorate the webpages.

The YAML header controls the layout of the page. On each page in the template there will be a </> button, to reveal what the underlying Markdown+YAML source file is pre-Quarto conversion into HTML, if you so wished to know!

While there is a bit of a learning curve, using template website builders like Quarto is easier than making your own website and looks more professional and is super fast once you get used to it. Having looked around Quarto seems to do a decent job blending these facets to give you the best experience in terms of simplicity, speed, flexibility and quality.

### What is this starter website?

The point of this website is as a more "feature rich" template.

The main [Quarto website](https://quarto.org/) is also feature rich, and a good source of insipration, but I thought it would be easier to have this website as a starting point, so you can copy this website to your own repo as explained below, as explained below, to get a more feature rich website out of the blocks.

You can publish this website using GitHub pages, or on other platforms, see [here](https://quarto.org/docs/publishing/index.html).

### Why should I have a website?

- Documenting what you have read, learnt and thought online is useful for yourself and others.
- Having a website where you can showcase yourself and your portfolio makes you stand out to employers (as does being active on GitHub, which writing on this website will make you appear).
- As alluded to before, there is a small initial learning curve, before the process becomes fast. But the skills required are mainstream and highly useful (e.g. GitHub, Markdown, HTML).

### Quick way to get your own website up and running in 3 minutes and 2 steps!

Assuming you have a GitHub account that is:

1. Click the template button (or click the fork button in the top right) on [this page](https://github.com/Smule11/Starter-Quarto-Website/) to make your own website repository.

2. Go into the settings of your new website repo, and edit the settings for "Pages" (on the middle left somewhere):

    Under 'build and deployment', select branch=main and folder=/docs. Then your website should go live!
    
    ----------
    
    ![github pages settings](https://user-images.githubusercontent.com/22969230/213680688-a73472b9-612e-4309-9dcf-c565af6afa09.png)
    
    ----------

### But how to edit the files...

This process has a couple of steps, but you need to edit it locally on your computer and render the markdown with Quarto, then push the files back up to GitHub.

You will need to have [Quarto](https://quarto.org/) and [Git installed on your computer and linked to your GitHub](https://www.codecademy.com/article/f1-u3-git-setup).

In short:

1.  then download your github repo containing your website to your local computer.

  Then you can edit the markdown files in a markdown (.md / .qmd) or notebook (.ipynb) editor of your choice.

2. Convert the markdown files into the HTML files, using Quarto. 

    Run "quarto render the_file_path_of_your_website_directory" in a terminal (or use the shortcut in VS Code / Jupyter Notebook if you have the relevant Quarto extension).

3. Push this local repository back up to the GitHub repository where your GitHub pages website is stored, using Git. 

### Advanced

You can enable comments [https://quarto.org/docs/output-formats/html-basics.html#commenting](https://quarto.org/docs/output-formats/html-basics.html#commenting).

You do so by going into the _quarto.yml file, finding the comments option, and entering the address to your github repo next to it pointing to where your blog lives. You should also have the Giscus app installed in this repo, see [here](https://github.com/apps/giscus).

You can also add javascript into your Quarto webpage, linked through the YAML header, to customise the webpage further. See [here](https://quarto.org/docs/reference/formats/html.html#includes).

### Useful links

[Quarto Guide](https://quarto.org/)
[Setting up Git and GitHub](https://www.codecademy.com/article/f1-u3-git-setup)

### Your Website Link

GOOD idea to change this link, to have your website URL here for easy access, for others and yourself.

[website URL](website URL)
