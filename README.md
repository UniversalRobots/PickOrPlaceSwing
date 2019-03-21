# PickOrPlaceSwing
URCap sample that mainly demonstrates the principle of ProgramModel, TreeNode and ProgramNodeFactory

Pick or Place Swing is a toy example that shows how to make changes to the program tree through the TreeNode API. The program node service (SwingProgramNodeService interface) is congured in such a way that it creates program node contributions that can only be inserted into the program tree by a URCap and not from the UI of PolyScope by the end user.

Information:
* Available from:
  * URCap API version 1.3.0.
  * PolyScope version 3.6.0/5.0.4.

Main API interfaces: ProgramModel, TreeNode, ProgramNodeFactory, SwingProgramNodeService, ContributionConfiguration
