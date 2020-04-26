# node-red-contrib-odoo-xmlrpc-filters-fileds
node function 
//msg.id = 1
msg.filters = [["|",["phone","ilike", msg.payload],["mobile","=", msg.payload]]],
//msg.offset = 0
//msg.limit = 0

msg.fields = (['name', 'fiscalcode']); 
var isSpecial = true;
return msg;


config search-read node 
res.partner
