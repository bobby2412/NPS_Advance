The steps involved to create a Network which consoists of 4 - PC  and 2 - switches( i have used a layer 2 switch ):
     * steup 4 pcs and add an ip address for each of them.
     * then connect the four pcs to a switch
     *configure 2 interfaces as vlan2 and the remaining two ad vlan3
     * now configure the interface connecting the two switches an a trunk port
     *check your configurations and test the configuration using ping 

commands:

conf t  
int f0/1
sw mode access
sw access valan _
int f0/2
sw mode trunk

