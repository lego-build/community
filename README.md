<p align="center"><img src="logo.svg#gh-light-mode-only" style="width: 350px"  alt="Logo" /></p>
<p align="center"><img src="LogoDark.svg#gh-dark-mode-only" style="width: 350px"  alt="Logo" /></p>
<h1 align="center">Community</h1>

A collection of different workflows and setups for front-end apps using [lego-build](https://lego-build.github.io). No need to reinvent the wheel, see how other developers structure their projects. <br /><br />

## Contributing

You can add your workflow to the list by forking the repository and creating a [pull request.](https://help.github.com/articles/creating-a-pull-request/) Create a new folder in the `workflows` directory to store your workflow. Each workflow folder contains the following files:

- templates.zip (A zip file containing your templates)
- lego.json (Your lego-build configuration file)
- [description.json](#description-file)<br /><br />

### Description file

The description.json has the following properties

| property    | type     | description                                                                                                                                                                                                                                        |
| ----------- | -------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| title       | `string` | The title of your workflow. It must contain only two words, and being unique isn't a necessity. Use it to shortly describe your workflow. Example: "Redux setup"                                                                                   |
| description | `string` | A longer description of your workflow. There's no limit, but try to make it just a few sentences long.                                                                                                                                             |
| author      | `object` | An object describing the owner of the workflow (you). It has two properties, `name` and `profileLink`. `name` for the name you want to appear, and `profileLink` for the link to your Github profile. Leave this property blank to stay anonymous. |

<br />

File example:

```json
{
  "title": "Redux workflow",
  "description": "Workflow to quickly setup redux files without having to worry about the boilerplate code. Contains templates for reducers, actions, hooks and stores",
  "author": {
    "name": "Akpeti Trust",
    "profileLink": "https://github.com/AkpetiTrust"
  }
}
```

<br />

### Guidelines

- Make your workflow description short, but descriptive.
- Use proper grammar in your workflow description. Capitalize, end sentences with a full stop, etc.
- Check your spelling.
- Your pull requests should be descriptive.

<br />
It's as simple as that to add your workflow! Just submit your pull request, and if you followed the guidelines, it'll be merged to master. Thanks for sharing your setup with the community 🙌🏾.
