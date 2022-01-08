<b>What is FLEXBOX?</b><hr>
A one-dimentional layout model.

Easy to design 
    <li> flexible & efficient layout</li>
    <li> distribute space among items</li>
    <li> control their alignments</li>


<b>Before flexbox there're below layout models</b>
    <li>Blocks for sections</li>
    <li>Inline for texts</li>
    <li>Table for two dimensional table data</li>
    <li>Positioned for explicit position of an element.</li>

<b>Why Flexbox?</b>
    <li>A lot of flexibility</li>
    <li>Arrange items</li>
    <li>Spacing</li>
    <li>Alignment</li>
    <li>Order of items</li>
    <li>Bootstrap 4 is built on top of the flex layout</li>


<b>Terminology</b>
    <li>Flex Container - Parent div</li>
    <li>Flex Items - Children divs</li>

Another notable pointis Axis.
    <li>Main Axis -> Left to Right</li>
    <li>Cross Axis -> Perpendicular to Main Axis. Top to Bottom</li> 


<b>Flex Container Properties:</b>
    <li><strong>display</strong> what defines a Flex container & is mandatory to work with Flexbox.</li>
    <li><strong>flex-direction</strong> defines in which the Flex items are placed in the container.</li>
    <li><strong>flex-wrap</strong> which is used to control the wrapping of items within a container.</li>
    <li><strong>flex-flow</strong> which is a shorthand for the combination of flex direction & flex wrap.</li>
    <li><strong>flex-justify</strong> that justifies content that defines the alignment of the items along the main axis.</li>
    <li><strong>align-items</strong> which defines how flex items are laid out along the cross axis.</li>
    <li><strong>align-content</strong> is similar to justify-content with the difference being this will align the cross axis instead of the main axis. Also aligned content works when there are multiple rows of Flex items in the container.</li>

<b>Property Values:</b>

<ul> Flex Properties
    <li><b>display</b> {flex, inline-flex}</li>
    <li><b>flex-direction</b> {row, row-reverse, column, column-reverse}</li>
    <li><b>flex-wrap</b> {nowrap(default), wrap, wrap-reverse}</li>
    <li><b>flex-flow</b> {flex-direction flex-wrap}</li>
    <li><b>justify-content</b> {flex-start, flex-end, center, space-between, space-around, space-evenly}</li>
    <li><b>align-items</b> {streatch(default), flex-start, flex-end, center, baseline}</li>
    <li><b>align-content</b> {flex-start, flex-end, center, space-between, space-around, space-evenly}</li>
    <li><b></b></li>
    <li><b></b></li>
    <li><b></b></li>
    <li><b></b></li>
</ul>

<ul> Flex item properties
    <li><b>order</b>: controls the order of items in the flex container. <br>Integer value</li>
    <li><b>flex-grow</b></li>
    <li><b>flex-shrink</b></li>
    <li><b>flex-basis</b></li>
    <li><b>flex</b></li>
    <li><b>align-self</b></li>
    <li><b></b></li>
</ul>