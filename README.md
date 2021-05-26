# node-red-contrib-odoo-xmlrpc-2021

Example message properties:

msg.filters = [["|",["phone","ilike", msg.payload],["mobile","=", msg.payload]]];
msg.filters = [[["bom_id","=", msg.bom_id]]];
msg.filters = [[["id","=", 23]]];

msg.offset = 0
msg.limit = 0

msg.fields = (['name', 'fiscalcode']); 
