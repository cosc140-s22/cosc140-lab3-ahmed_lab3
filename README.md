# COSC140 lab 3

## Answers to the five questions at the end of the lab description

1.  shark = Product(name = "stuffed shark", description = "soft, but with pointy teeth", price=45.00, minimum_age_appropriate=2, maximum_age_appropriate=43)
    shark.save()  

2. Product.objects.all()

3. shark = Product.objects.get(pk=6)
   shark.price = 22.5
   shark.save()
   Product.objects.get(pk=6)

4. shark = Product.objects.get(pk=6)
   shark.delete()
    Deleted products have an id of None.

5. objects = Product.objects.filter(price__lt=10).filter(name__icontains='stuff') 

## Lab feedback

 * How long did you spend on this lab?
   * A few hours

 * What did you think about it?  What was good?  What could be improved?
   * I thought it was good and helped me learn more about Django models.

## Feedback

S

All looks good!

