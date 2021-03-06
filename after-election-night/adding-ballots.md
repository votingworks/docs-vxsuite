# Process Late Ballots

You may receive properly post-marked absentee ballots for five days after election day that need to be counted. To add these ballots to unofficial results:

1. Scan late-received ballots on VxCentralScan, preserving the election-night scans
2. Export the CVRs, including both election-night and late-received.
3. Import the new CVR file in VxAdmin
4. Print tally report
5. Export results
6. Upload results to SEMS

VotingWorks recommends scanning and tabulating all late-received ballots at once though you may process late-received ballots multiple times by repeating these steps.

## Scan Late-Received Ballots

When you turn on VxCentralScan, you should see previous batches scanned on election night. You can scan new batches for the properly postmarked ballots received after election night, using the normal scanning instructions, including adjudicating ballots that don't scan. See [Central Scanning](../election-ops/scanning-ballots.md).

## Export CVR

After scanning all late-received ballots, export the combined CVR file that contains all ballots, both election-night and late-received. See instructions under [Tally Results](../election-ops/tabulating-results.md), the portion on exporting CVRs.

## Import CVR

In VxAdmin, upload the new CVR file. Select _`Import CVR Files`_.

![](<../.gitbook/assets/image (123) (1).png>)

Select _`Import`_ for the CVR file you want to import.

![](<../.gitbook/assets/image (85) (1).png>)

## Export Results

To export results with the new CVR included, follow the process used on election night, described in [Export Results](../election-ops/export-results.md).
