# Journal of Open Research Software

This Quarto format will help you create documents for the Journal of Open Research Software. For more about Quarto and how to use
format extensions, see <https://quarto.org/docs/journals/>.

## Creating a New Article

You can use this as a template to create an article for the Biophysical Journal. To do this, use the following command:

```quarto use template NOVA-IMS-Innovation-and-Analytics-Lab/jors```

This will install the extension and create an example qmd file and bibiography that you can use as a starting place for your
article.

## Installation For Existing Document

You may also use this format with an existing Quarto project or document. From the quarto project or document directory, run the
following command to install this format:

```quarto install NOVA-IMS-Innovation-and-Analytics-Lab/jors```

## Usage

To use the format, you can use the format name `jors-pdf`. For example:

```quarto render article.qmd --to jors-pdf```

or in your document yaml

```yaml
format:
  pdf: default
  jors-pdf:
    keep-tex: true    
```
