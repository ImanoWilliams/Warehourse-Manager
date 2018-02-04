# Warehourse-Manager

Problem Description:
<br />
Write a program to monitor the flow of an item into and out of a warehouse. The warehouse will have numerous deliveries
and shipments for this item (a widget) during the time covered. A shipment is billed at a profit of 50 percent over the cost
of a widget. Unfortunately, each shipment received may have a different cost associated with it. The accountants for the
firm have instituted a last-in, first-out system for filling orders. This means that the newest widgets are the first ones sent
out to fill an order. This member function of inventory can be represented using a stack. The push operator will insert a
shipment received. The pop operator will delete a shipment out.
<br />
Input:
<br />
Input data will come from a file named hw1in.txt and will consist of the following:
- s or o: shipment received or an order to be sent
- amount: The quantity received or shipped out
- cost: cost per widget (for received shipments only)
- vendor: a character string that names the company sent to or received from
For example, the data fragment below indicates that 100 widgets were received from RCA at $10.50 per widget and 50
were shipped to Boeing:
s 100 10.50 RCA
o 50 Boeing
Since there may not be enough widgets to fill an order in the warehouse, all orders should be placed on a queue while they
are waiting to be filled. Orders are placed and fulfilled in first-come first-served order.
<br />
Output:
<br />
Output for an order (hw1out.txt) will consist of vendor, the quantity and the total price for all the widgets in the order.
(Hint: Each widget price is 50 percent higher than its cost. The widgets to fill an order may come from multiple shipments
with different costs.).
