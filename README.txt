Inclass assessment
class Basket:
     def __init__(self,line_items,discounts_code):
        items_list= self.line-items
        coupen_code=self.discount_code
        
class Shop:
    def __init__(self,p_list,d_list):
        price_list=self.p_list
        discount_list=self.d_list
    def calculation(self,basket_list
    
    
    
    class Basket:
     def __init__(self,line_items,discounts_code):
        self.items_list=line_items
        self.coupen_code=discount_code
        
class Shop:
    def __init__(self,p_list,d_list):
        self.price_list=p_list
        self.discount_list=d_list
        
    def discount_basket_price(self,basket,basket_cost):
        if(basket.coupen_code in self.discount_list):
            print("discount")
            return basket_cost-(self.discount_list[basket.coupen_code])
        return basket_cost
        
    def basket_price_calculation(self,basket):
        print("basket values",basket)
        basket_cost=0
        item_cost=0
        print(self.price_list)
        
    
    
    def order_baskets_by_price(self,basket_list):
        print("list of baskets",basket_list)
    
        return "bucket price list"
    
    
#Price dictionary as item : price in euros
#discount list with coupen codes in list
s= shop({"eggs":10,"rice":20,"bread":30},["egg2","rice1","bread"])
b1=basket({"eggs":3,"rice:2"},"egg2")
b2=basket({"eggs":5,"rice:3"},"egg2")
b3=basket({"eggs":6,"rice:3"},"egg2")
b4=basket({"eggs":2,"rice:1"},"egg2")
basket_prices = s.order_baskets_by_price([b1,b2,b3,b4])

print(basket_prices)
    
    
