# homework-2
Ödev 2 : Yazılan mimaride 1 adet test yazmanız ve tamamlamanız. 

#Test with Selenium And Cucumber

Feature: Add shopping item

  Scenario: Add shopping item
    Given Navigate to the Amazon website
    And Search for product
    And Click search button
    And Select the first product from list
    When Add product to the cart
    Then Control that the product has been successfully added to cart
    Then Return to cart