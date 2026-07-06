# Documents for ${{values.app_name}}

This application has two endpoints:
- `python-app.test.com/api/v1/info`
- `python-app.test.com/api/v1/healthz`

# How to access the app?

You can access the app by accessing this URL: `${{ values.app_name }}-${{ values.app_env }}.test.com/api/v1/info`