Features Matrix
---------------

PTVS can be installed in the following editions of Visual Studio:

* [Visual Studio 2013 Express for Web](http://www.microsoft.com/en-us/download/details.aspx?id=40747) - Update 2 required.
* [Visual Studio 2013 Express for Desktop](http://www.microsoft.com/en-us/download/details.aspx?id=40787) - Update 2 required.
* Visual Studio 2013 Pro or higher
* Visual Studio 2012 Pro or higher
* Visual Studio 2010 Pro or higher - Service Pack 1 required and .NET 4.5 required.

Below is a feature matrix for the supported editions of Visual Studio.  Features that are not available are <mark>highlighted</mark>.

|| **Python Support**                            || **2010 Pro+**    || **2012 Pro+**    || **2013 Pro+**    || **2013 Web**     || **2013 Desktop** ||
|| &nbsp;Multi interpreters management           || yes              || yes              || yes              || yes              || yes              ||
|| &nbsp;Auto-detect popular interpreters        || yes              || yes              || yes              || yes              || yes              ||
|| &nbsp;Add custom interpreters                 || yes              || yes              || yes              || yes              || yes              ||
|| &nbsp;Virtual Environments                    || yes              || yes              || yes              || yes              || yes              ||
|| &nbsp;Pip/Easy Install                        || yes              || yes              || yes              || yes              || yes              ||
|| **Project System**                            || **2010 Pro+**    || **2012 Pro+**    || **2013 Pro+**    || **2013 Web**     || **2013 Desktop** ||
|| &nbsp;New project from existing code          || yes              || yes              || yes              || yes              || yes              ||
|| &nbsp;Show all files                          || yes              || yes              || yes              || yes              || yes              ||
|| &nbsp;Source control                          || yes              || yes              || yes              || yes              || yes              ||
|| &nbsp;Git integration                         || <mark>no</mark>  || yes <sup>1</sup> || yes              || yes              || yes              ||
|| **Editing**                                   || **2010 Pro+**    || **2012 Pro+**    || **2013 Pro+**    || **2013 Web**     || **2013 Desktop** ||
|| &nbsp;Syntax highlighting                     || yes              || yes              || yes              || yes              || yes              ||
|| &nbsp;Completions                             || yes              || yes              || yes              || yes              || yes              ||
|| &nbsp;Signature help                          || yes              || yes              || yes              || yes              || yes              ||
|| &nbsp;Quick info                              || yes              || yes              || yes              || yes              || yes              ||
|| &nbsp;Object browser / Class view             || yes              || yes              || yes              || yes              || yes              ||
|| &nbsp;Navigation bar                          || yes              || yes              || yes              || yes              || yes              ||
|| &nbsp;Go to definition                        || yes              || yes              || yes              || yes              || yes              ||
|| &nbsp;Navigate to                             || yes              || yes              || yes              || yes              || yes              ||
|| &nbsp;Find all references                     || yes              || yes              || yes              || yes              || yes              ||
|| &nbsp;Auto indentation                        || yes              || yes              || yes              || yes              || yes              ||
|| &nbsp;Formatting                              || yes              || yes              || yes              || yes              || yes              ||
|| &nbsp;Refactor - Rename                       || yes              || yes              || yes              || yes              || yes              ||
|| &nbsp;Refactor - Extract method               || yes              || yes              || yes              || yes              || yes              ||
|| &nbsp;Refactor - Add/Remove import            || yes              || yes              || yes              || yes              || yes              ||
|| &nbsp;Pylint <sup>new</sup>                   || yes              || yes              || yes              || yes              || yes              ||
|| **Interactive Window**                        || **2010 Pro+**    || **2012 Pro+**    || **2013 Pro+**    || **2013 Web**     || **2013 Desktop** ||
|| &nbsp;Interactive Window                      || yes              || yes              || yes              || yes              || yes              ||
|| &nbsp;IPython with inline graphs              || yes              || yes              || yes              || yes              || yes              ||
|| **Desktop**                                   || **2010 Pro+**    || **2012 Pro+**    || **2013 Pro+**    || **2013 Web**     || **2013 Desktop** ||
|| &nbsp;Console/Windows application             || yes              || yes              || yes              || yes              || yes              ||
|| &nbsp;IronPython WPF (with XAML designer)     || yes              || yes              || yes              || yes              || yes              ||
|| &nbsp;IronPython Windows Forms                || yes              || yes              || yes              || yes              || yes              ||
|| **Web**                                       || **2010 Pro+**    || **2012 Pro+**    || **2013 Pro+**    || **2013 Web**     || **2013 Desktop** ||
|| &nbsp;Django web project                      || yes              || yes              || yes              || yes              || <mark>no</mark>  ||
|| &nbsp;Bottle web project <sup>new</sup>       || yes              || yes              || yes              || yes              || <mark>no</mark>  ||
|| &nbsp;Flask web project <sup>new</sup>        || yes              || yes              || yes              || yes              || <mark>no</mark>  ||
|| &nbsp;Generic web project <sup>new</sup>      || yes              || yes              || yes              || yes              || <mark>no</mark>  ||
|| &nbsp;Web Deploy to Azure Web Site            || yes <sup>2</sup> || yes              || yes              || yes              || <mark>no</mark>  ||
|| &nbsp;Web Deploy to Azure Web Role            || yes <sup>2</sup> || yes <sup>3</sup> || yes <sup>4</sup> || yes <sup>4</sup> || <mark>no</mark>  ||
|| &nbsp;Run in Azure emulator                   || yes <sup>2</sup> || yes <sup>3</sup> || yes <sup>4</sup> || yes <sup>4</sup> || <mark>no</mark>  ||
|| **Django Templates**                          || **2010 Pro+**    || **2012 Pro+**    || **2013 Pro+**    || **2013 Web**     || **2013 Desktop** ||
|| &nbsp;Debugging                               || yes              || yes              || yes              || yes              || <mark>no</mark>  ||
|| &nbsp;Completions                             || yes              || yes              || yes <sup>5</sup> || yes <sup>5</sup> || <mark>no</mark>  ||
|| &nbsp;Completions for CSS, JS <sup>new</sup>  || <mark>no</mark>  || <mark>no</mark>  || yes <sup>5</sup> || yes <sup>5</sup> || <mark>no</mark>  ||
|| **Debugging**                                 || **2010 Pro+**    || **2012 Pro+**    || **2013 Pro+**    || **2013 Web**     || **2013 Desktop** ||
|| &nbsp;Debugging                               || yes              || yes              || yes              || yes              || yes              ||
|| &nbsp;Debugging without a project             || yes              || yes              || yes              || yes              || yes              ||
|| &nbsp;Debugging - Attach to existing          || yes              || yes              || yes              || <mark>no</mark>  || yes              ||
|| &nbsp;Mixed-Mode debugging                    || <mark>no</mark>  || yes              || yes              || <mark>no</mark>  || yes              ||
|| &nbsp;Remote debugging (Windows/Linux/Mac)    || yes              || yes              || yes              || <mark>no</mark>  || yes              ||
|| &nbsp;Debug interactive window                || yes              || yes              || yes              || yes              || yes              ||
|| **Profiling**                                 || **2010 Pro+**    || **2012 Pro+**    || **2013 Pro+**    || **2013 Web**     || **2013 Desktop** ||
|| &nbsp;Profiling                               || yes              || yes              || yes              || <mark>no</mark>  || <mark>no</mark>  ||
|| **Test**                                      || **2010 Pro+**    || **2012 Pro+**    || **2013 Pro+**    || **2013 Web**     || **2013 Desktop** ||
|| &nbsp;Test explorer                           || <mark>no</mark>  || yes              || yes              || yes              || yes              ||
|| &nbsp;Run test                                || <mark>no</mark>  || yes              || yes              || yes              || yes              ||
|| &nbsp;Debug test                              || <mark>no</mark>  || yes              || yes              || yes              || yes              ||

1. Git support for VS 2012 is available in the Visual Studio Tools for Git extension, available on the [Visual Studio Gallery](http://visualstudiogallery.msdn.microsoft.com/abafc7d6-dcaa-40f4-8a5e-d6724bdb980c).

2. Deployment to Azure Web Site or Web Role requires [Azure SDK for .NET 2.1 - VS 2010 SP1](http://go.microsoft.com/fwlink/?LinkId=313855).  Later versions don't support VS 2010.

3. Deployment to Azure Web Role requires [Azure SDK for .NET 2.2 - VS 2012](http://go.microsoft.com/fwlink/?LinkId=323511) or later.

4. Deployment to Azure Web Role requires [Azure SDK for .NET 2.2 - VS 2013](http://go.microsoft.com/fwlink/?LinkId=323510) or later.

5. Django template editor in Visual Studio 2013 has some known issues that are resolved by installing Update 2.