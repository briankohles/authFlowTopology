# This is a design concept for how to document IT architectural flows
This example shows the flow of a basic web app from the perspective of the webGUI, that basic flow is then expanded to show the more complex flows of the authN/athZ processes, as well as the architecture topology of those components.

This is not intended to be a detailed description of every aspect of the flow. But more of a high level overview of the process as a whole. This would be intended for use in an enterprise environment where each team only handles one portion of the flow. This documentation would serve to keep all teams informed of how the processes of the other teams work.

The overall thought is that each node could be clicked/zoomed to expand that bit of the puzzle to get more details.

The final goal will be to have these details stored in a wiki where each team could modify their portion to keep it up to date.

The flow is intended to be used for intended design so items would **NOT** be queried from their actual config.

The flows will be generated in GraphViz DOT format.

#Flow
## Web Flow will include
* major decision points
	* Login
	* Register
	* Forgot Password
	* Home Page
	* About page

## AuthN/AuthZ
* Access Management Software
* LDAP

# Arch/Topology
* Include all major pieces
	* Firewall
	* GLB
	* LB
	* Host

# Additional items to include?
* Logging (note where each component logs & the source for correlation)
* Node types (web/am/fw/lb/ldap/SIEM)
* Node Owner