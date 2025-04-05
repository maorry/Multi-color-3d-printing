<header>

<!--
  <<< Author notes: Course header >>>
  Include a 1280×640 image, course title in sentence case, and a concise description in emphasis.
  In your repository settings: enable template repository, add your 1280×640 social image, auto delete head branches.
  Add your open source license, GitHub uses MIT license.
-->

# Automatic multicolor printing

I always wanted to print multi color prints but it was always out of my reach. 

The past year I've been working on a project that will change everything you know about multi color printing.

### With only one stepper motor and one hotend.

</header>

## The idea.

The idea is to have a piece that holds the filaments (pictures 12 and 9), this part is placed on an aluminum profile that holds several of them (depending on the length of the profile and the length of movement on the X axis), the second part is the extruder (picture 11).
The two parts are connected together by magnets (you can see in the pictures).
The third part (picture 6) has a ball bearing that presses the filament with a spring.

## So how does it actually work?

Like any other tool changer but with a twist.

1. The desired color is selected.
2. The extruder moves towards the part that holds the filament
3. A piece of rod goes into the middle hole in the third part.
4. The extruder moves to the side so that the third part moves and thus creates a gap between the gear and the ball bearing.
5. Once there is a gap, the extruder moves forward towards the filament holder so that it fits exactly in the gap created, held by magnets to the extruder.
6. The extruder moves a little to the side so that the filament holder detaches from the aluminum profile that holds it and at the same time releases the third part so that it presses on the filament.
7. The extruder moves back until it is released from the rod that goes into the third part.
8. Continues printing.

### There are 2 important sensors on the extruder:

1. A sensor that transmits whether a filament holder is present on the extruder or not.
2. A sensor that transmits when the filament holder can be removed from the extruder and when not.

   
<!--
  <<< Author notes: Step 1 >>>
  Choose 3-5 steps for your course.
  The first step is always the hardest, so pick something easy!
  Link to docs.github.com for further explanations.
  Encourage users to open new tabs for steps!


## Step 1: Enable GitHub Pages

_Welcome to GitHub Pages and Jekyll :tada:!_

The first step is to enable GitHub Pages on this [repository](https://docs.github.com/en/get-started/quickstart/github-glossary#repository). When you enable GitHub Pages on a repository, GitHub takes the content that's on the main branch and publishes a website based on its contents.

### :keyboard: Activity: Enable GitHub Pages

1. Open a new browser tab, and work on the steps in your second tab while you read the instructions in this tab.
1. Under your repository name, click **Settings**.
1. Click **Pages** in the **Code and automation** section.
1. Ensure "Deploy from a branch" is selected from the **Source** drop-down menu, and then select `main` from the **Branch** drop-down menu.
1. Click the **Save** button.
1. Wait about _one minute_ then refresh this page (the one you're following instructions from). [GitHub Actions](https://docs.github.com/en/actions) will automatically update to the next step.
   > Turning on GitHub Pages creates a deployment of your repository. GitHub Actions may take up to a minute to respond while waiting for the deployment. Future steps will be about 20 seconds; this step is slower.
   > **Note**: In the **Pages** of **Settings**, the **Visit site** button will appear at the top. Click the button to see your GitHub Pages site.
-->
<footer>

<!--
  <<< Author notes: Footer >>>
  Add a link to get support, GitHub status page, code of conduct, license link.
-->

---

Get help: [Post in our discussion board](https://github.com/orgs/skills/discussions/categories/github-pages) &bull; [Review the GitHub status page](https://www.githubstatus.com/)

&copy; 2023 GitHub &bull; [Code of Conduct](https://www.contributor-covenant.org/version/2/1/code_of_conduct/code_of_conduct.md) &bull; [MIT License](https://gh.io/mit)

</footer>
