# Author: Rajendra Maharjan
# Sample code for deleting item from struct mapping

# How to delete an item from struct mappings?
  This is a sample solidity code that shows how we can delete item on struct mapping.
  
  Deleting item using "delete items[index]" doesn't delete actual array index place holder but removes the contents only. So we need to   move last item to the deleting item index and decrease the itemCount
