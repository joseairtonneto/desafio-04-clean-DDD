# desafio-04-clean-DDD

# Entidades de domínio
- Product
- Sale
- Storage
- Notification
- Order

# Casos de uso
- RegisterProduct (Cria o produto)
- GetProducts (Busca todos produtos)
- GetProductById (Busca produto por Id)
- AddProductToStorage (Adiciona o produto no estoque)
- CreateSale (Cria uma venda, com isso reduz no estoque e verifica a quantidade mínima)
- SendNotification (Envia a notificação, seja no sistema ou por email)
- GetSalesByPeriod (Busca vendas por período, trazendo os dados de queantidade de vendas, lucro por produto e quais produtos estão vendendo melhor)
- GetStorageByPeriod (Busca estoque por período)
- CreateOrder (Cria ordem de compra)
- GetOrders (Busca ordens de compras)
- GetOrderById (Busca ordem de compra por Id)
- GetOrderShipmentUpdates (Busca atualizações de ordem de compra)
