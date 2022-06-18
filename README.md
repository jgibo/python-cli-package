CLI Package template based on https://pybit.es/articles/how-to-package-and-deploy-cli-apps/

Run directly from repo: `python mypackage` (Note: Different entry point, \_\_main\_\_.py file)

Dev editable install: `pip install -e .`

Build: `python -m build`

Install CLI from repo: (after build) `pip install dist/mypackage-METADATA-.whl`
