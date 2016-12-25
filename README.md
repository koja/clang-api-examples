# clang-api-examples

Examples of [clang](http://clang.llvm.org/) compiler [API](http://clang.llvm.org/docs/Tooling.html) usage.

Official clang API documentation ([1](http://clang.llvm.org/docs/index.html), [2](http://clang.llvm.org/doxygen)) is a work in progress. Meanwhile unofficial learning resources are scattered all around the internet. The goal is to create a list of code examples so that full power of proper tools (grep, find, etc.) can be unleashed instead of using web search engines. All other resources are welcome as well.

# Looking forward to pull-requests!

Current stage is **initial hoarding**. All **freely available** resources (no matter their state, age, clang compatibility or ability to build) are very welcome.

Please add resources:

* **code examples in form of git repository** as **submodules** structured as `<creator>/<project>`.
* **other** resources (including other lists of resources) as **links** to the [Sources](#sources) section below.

In case of doubt or need of help please create an [issue](../../issues/new) and let's discuss it.

## git submodules
[How to dealing with git submodules?](https://git-scm.com/book/en/v2/Git-Tools-Submodules)

* **clone** whole repository including submodules: `git clone --recursive`
* **update** every submodule to the latest commit in remote repository: `git submodule update --recursive --remote`
* **add** submodule: `git submodule add`

# Sources

Please use one or more appropriate "tags" at the end of line. Currently used tags are: `(list) (code)`.

* http://clang.llvm.org/docs/ExternalClangExamples.html (list)(code)
