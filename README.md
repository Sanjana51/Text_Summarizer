import setuptools

with open("README.md", "r",encoding="utf-8") as f:
      long_description =f.read()


__version__="0.0.0"

REPO_NAME ="Text_Summarizer"
AUTHOR_USER_NAME = "Sanjana51"
SRC_REPO = "Text_Summarizer"
AUTHOR_EMAIL = "sanjanasingh83963@gmail.com"




setuptools.setup(
    name=SRC_REPO,
    version= __version__,
    author=AUTHOR_USER_NAME,
    author_email=AUTHOR_EMAIL,
    description="A small python package for NLP app",
    Long_description=long_description,
    Long_description_content="text/markdown",
    url
)