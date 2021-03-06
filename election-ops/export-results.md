---
description: >-
  VxAdmin exports SEMS-ready results files that include the results tabulated by
  VotingWorks equipment and, optionally, results exported from GEMS.
---

# Export Results

## Export Results for SEMS

{% hint style="warning" %}
If you are using TSX machines alongside VotingWorks for absentee ballots, you must first import the results from GEMS. Read the [Import GEMS Results](export-results.md#appendix-import-gems-results) appendix and then return here.
{% endhint %}

To export SEMS results, scroll to the Export Options **** section and select _`Save Results File.`_

![](<../.gitbook/assets/image (80).png>)

If you haven't inserted a USB drive, you will be prompted to do so. Election Manager will create a clear filename that includes the date and ask you to  confirm that you want to _`Save.`_

![](<../.gitbook/assets/image (83).png>)

The file will be saved to the USB drive. Eject the USB drive by selecting _`Eject USB`_, when the screen indicates it's safe to do so, remove the USB drive.

## Upload to SEMS

Connect the USB drive with the exported results to a computer connected to SEMS. Once connected, you will need to copy the results file to your local computer drive as SEMS does not recognize USB drives. You can launch SEMS after you have copied the appropriate results file to your local computer.

In SEMS, navigate to the Election Management view for the corresponding election and select _`Election Results`_ in the left navigation. From the results view, select _`Import Results` _ and then browse to the copied results file on your computer from the subsequent import dialog. Close the import dialog once finished importing.

Your election results should now be presented to you in SEMS. If results are not immediately presented, select the _`Refresh Wizard Status`_in the bottom left of the screen. You should see results after refreshing.

## Appendix: Import GEMS Results

{% hint style="warning" %}
This step applies only if you are utilizing TSX machines for in-person voting alongside VotingWorks for absentee ballots.
{% endhint %}

First, you will need to save your in-precinct TSX results files from GEMS to a USB drive. This does not need to be the same USB drive as the one you use for VotingWorks, but it can be.

Next, you will load the results file you got from the GEMS server into the VotingWorks tabulation screen . Select _`Import External Results File.`_

![](<../.gitbook/assets/image (181).png>)

Navigate the files on the USB drive to find and select the GEMS results file. It should load alongside your CVR file.

At that point, the _Unofficial Full Election Tally Report_ will show the combined VotingWorks and GEMS results.

![](<../.gitbook/assets/image (147) (1).png>)
