<p>Hello, everyone.</p>
<p>I coded an algorithm to solve Traveling Thief Problem (TTP)</p>
<p>TTP is  a combination of 2 well known optimization problems, the Traveling Salesman Problem (TSP) and the Knapsack Problem (KP), this problem presents an scenario where we have a thief that has to travel through n quantity of cities while taking items of this cities without exceeding the capacity of the bag he
 is using to carry the items, the main objective in this problem is to find a
 route where the thief expends the less time possible while getting the most
 profit from the items.</p>
 <p>Center-end insertion algorithm steps:</p>
 <ol>
    <li>Obtain the value/weight division of the items.</li>
    <li>Order the items from highest to lowest according to the previous result.</li>
    <li>Choose the items from top to bottom, provided that the sum of the weights does not exceed the capacity of the backpack.</li>
    <li>Obtain the cities where the previously chosen items are available.</li>
    <li>Start the routing of these cities, through the following:</li>
    <li>Find the 2 closest nodes to the starting point.</li>
    <li>The furthest node of these 2 will be the first node to visit; it will be placed at the beginning of the route.</li>
    <li>The closest node will be placed as the last city to visit, before returning to the starting point.</li>
    <li>From these 2 nodes, placed at the beginning and end of the route, the nodes closest to these will be searched for and assigned as the next node (if it is the extreme left) or previous node (extreme right).</li>
    <li>Repeat step 9 until there is only one node left, which will stay in the middle of the path.</li>
</ol>
