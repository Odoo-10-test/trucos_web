# Trucos Web
## Cargar Datos Masivos

Agregando un CSS
note_templates.xml
```
<?xml version="1.0" encoding="utf-8"?>
<odoo>
        <template id="assets_backend" name="note assets" inherit_id="web.assets_backend">
            <xpath expr="." position="inside">
                <link rel="stylesheet" href="/note/static/src/css/note.css"/>
            </xpath>
        </template>
</odoo>

```
Agregando JS
```
<?xml version="1.0" encoding="utf-8"?>
<odoo>
        <template id="assets_backend" name="crm assets" inherit_id="web.assets_backend">
            <xpath expr="." position="inside">
                <link rel="stylesheet" href="/crm/static/src/css/crm.css"/>
                <!-- Planner assets -->
                <script type="text/javascript" src="/crm/static/src/js/web_planner_crm.js"></script>
                <!-- Salesteam dashboard asset -->
                <script type="text/javascript" src="/crm/static/src/js/sales_team_dashboard.js"></script>
                <script type="text/javascript" src="/crm/static/src/js/tour.js"></script>
            </xpath>
        </template>
</odoo>
```

