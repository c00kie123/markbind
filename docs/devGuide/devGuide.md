{% set title = "Contributing" %}
<span id="title" class="d-none">{{ title }}</span>

<frontmatter>
  title: "{{ title }}"
  layout: devGuide.md
</frontmatter>

<h1 class="display-3">Developer guide</h1>

# {{ title }}

<div class="lead">

**Thank you for your interest in contributing!** We're glad you want to help. We welcome PRs, especially from students.
</div>

**First, do take note of** [**our _code of conduct_** (from SE-EDU)](https://se-education.org/guides/guidelines/codeOfConduct.html). Reporting bugs or submitting feature suggestions in [our issue tracker](https://github.com/markbind/markbind) can help too.

**Second, ensure you have a basic knowledge** of the following:

* JavaScript (ES6)
* Node.js
* HTML & CSS
* Markdown
* Command-line environment

**Third, ensure you have spent time with MarkBind and familiar with the content of the [user guide](https://markbind.org/).** It's important to know the product well before you start contributing code.

**Now, follow these steps to get started on contributing:**

1. **Set up the project** in your computer (see [the _Setting up_ page](development/settingUp.html))
1. **Learn our workflow** (see [the _Workflow_ page](development/workflow.html))
1. **(Optional) Go through our onboarding bootcamp** (see [the _Onboarding Bootcamp_ page](bootcamp/intro.html))
1. **Submit PRs** as per the workflow. If you encounter any problems, post in [our issue tracker](https://github.com/markbind/markbind/issues).
1. **(Optional) Add yourself to the contributors list!** (Bug reported? PR merged? If you haven't done so already, [add](https://allcontributors.org/docs/en/bot/usage#all-contributors-add) yourself to our list of contributors!)

**We look forward to your PR. Happy coding!**

{% from "njk/common.njk" import previous_next %}
{{ previous_next('', 'bootcamp/intro') }}
