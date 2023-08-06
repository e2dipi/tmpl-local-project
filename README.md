# README - *Local Project Template*

---

<div style="
    font-size: normal;
    margin: 0 auto 5ex auto;
    width: 40em;"
>
<div style="font-size: 95%; text-align: justify;">
<div style="
  font-size:135%;
  text-align: center;
  font-weight: bold;
  margin: 0 0 .75ex 0;
  font-variant: small-caps;"
>Abstract</div>
<div style="text-align: justify">
<i>This template provides a folder hierarchy for holding one or more projects sharing common
resources.  Its versatile structure is suitable for all sorts of projects, regardless of their size,
complexity, or nature. It is not meant to be used as a repository template, but rather as a template
for a local folder structure that will contain one or more repositories. Note that it is not to be
confused with a mono-repo either since its root folders are not meant to be versioned. The
contents of the <code style="font-style: normal">/workspace(s)</code> folder, however, may consist of one or more repositories.</i>
</div></div></div>
<div style="
   width: 100%;
   text-align: center;
    margin-bottom: 5ex;"
>

[![GitHub issues](https://img.shields.io/github/issues/e2d2ipi/tmpl-projects-root-folder.svg)](https://github.com/e2d2ipi/tmpl-projects-root-folder/issues)
[![GitHub forks](https://img.shields.io/github/forks/e2d2ipi/tmpl-projects-root-folder.svg)](https://github.com/e2d2ipi/tmpl-projects-root-folder/network)
[![GitHub stars](https://img.shields.io/github/stars/e2d2ipi/tmpl-projects-root-folder.svg)](https://github.com/e2d2ipi/tmpl-projects-root-folder/stargazers)
[![GitHub license](https://img.shields.io/github/license/e2d2ipi/tmpl-projects-root-folder.svg)](https://github.com/e2d2ipi/tmpl-projects-root-folder/blob/main/LICENSE.md)

</div>
<div>

<!-- @import "[TOC]" {cmd="toc" depthFrom=2 depthTo=6 orderedList=false} -->
<details open style="margin: 14pt 0pt 24pt 10pt">
<summary style="margin-left: -8pt; font-weight: bold; font-size: larger; font-variant: small-caps">
<span style="margin-left: 3pt">Table of contents<span></summary>

<!-- code_chunk_output -->

- [Install](#install)
- [Contents](#contents)
- [Highlights](#highlights)
- [Roadmap](#roadmap)
- [Contributors](#contributors)
- [Project's License](#projects-license)

<!-- /code_chunk_output -->

</detail>
</div>

## Install

As it is not meant to be used as a repository, this template is not saved as a *GitHub template* and,
 therefore, cannot be used to [instantiate a new repository](https://tinyurl.com/z427byf6).
 Instead, it is meant to be downloaded and used as a local folder structure template. To do so,
 simply download the latest release from the [releases page](https://tinyurl.com/4f3ekkzb) and
 extract it to the desired location. Alternatively, you can clone the repository and remove the `.git`
 folder<sup>1</sup> as well as all the files and folders that are not needed: the structure you should
 end up with contains only folders and `.gitkeep` files and is shown in the tree of the next section.
 Also, the `workspace(s)` folder should be renamed to singular or plural form according to the
 number of workspaces the project will contain.

<ol style="font-style: italic; padding-left: 10pt">
  <li>
      <p>
        Note that the <code>.git</code> folder is hidden by default. You may need to enable the
        display of hidden files and folders in your file explorer to see it. Alternatively, you can use the
        following command to remove it.
      </p>
      <ul style="font-style: italic; padding-left: 10pt">
        <li>In a <code>Bash terminal</code>:
          <pre style="color:inherit; margin-top: 5pt">rm -rf .git</pre>
        </li>
        <li>In a <code>PowerShell terminal</code>:
          <pre style="color:inherit; margin-top: 5pt">Remove-Item -Recurse -Force .git</pre>
        </li>
      </ul>
  </li>
</ol>

## Contents

@@CONTENTS@@

## Highlights

@@HIGHLIGHTS@@

## Roadmap

Planned features and improvements as well as known issues and other topics of interest concerning
this template's development status are embedded in its `.gitkeep` files in the form of
[Todo Tree comments](https://marketplace.visualstudio.com/items?itemName=Gruntfuggly.todo-tree). The most important ones are also listed here for convenience:

- [ ]  @@ROADMAP_ENTRY_1@@, if applies
- [ ]  @@ROADMAP_ENTRY_2@@, if applies
- [ ]  etc ...


@@ROADMAP@@

## Contributors

@@Contributors@@

## Project's License

This project is licensed under the **MIT License** &nbsp;-&nbsp; *see the
file [LICENSE](./LICENSE) for details.*

<!-- EDIT Make sure that all @@TO-BE-REPLACED@@  were either replaced or deleted with their associated contents. Delete this comment only once this is done! [template]  -->
