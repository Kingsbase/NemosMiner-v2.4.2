 # NemosMiner-v2.4.2
 
 Added functionality:

prerun feature

Ability to run a batch prior switching to a specific algo.
For example, can be used to set OC via nvidiaInspector
Simply create a file named .bat in prerun folder
If .bat does not exist, will try to launch prerun/default.bat

ahashpoolplus

Added ahashpoolplus as a pool.
Simply use -PoolName ahashpoolplus in start.bat
Uses calculations based on 24hractual and currentestimate ahashpool prices to get more realistic estimate.
Includes some trust index based on past 1hr currentestimate variation from 24hr.
This shows less switching than following Current Estimate and more switching that following the 24hr Actual.
AND is NOT sensible to spikes.
Better profitability on our rigs.
Test and share the results on yours.
Only for ahashpool. Working on expanding the feature to other pools.

Algo switching log

Added simple algo switching log in csv. switching.log file found in Logs folder.
Can be easily imported in excel as csv file. include wallet so donation rounds can be clearly identified as well
    
 
 This is a free project feel free to donate be much appreciated:

aaronsace = 1MsrCoAt8qM53HUMsUxvy9gMj3QVbHLazH

nemo = 1QGADhdMRpp9Pk5u5zG1TrHKRrdK5R81TE

MrPlus = 1Hgmj84fzSbgYbv2QgrDmBNWSL7762Ry8P


*****
 
NemosMiner-v2.4.2 Monitors mining pools in real-time in order to find the most profitable Algo /
 Auto Benchmarks Each algo to get optimal speeds / 
Fully automated / 
Auto Downloads Miners

instructions:

edit startpoolname.bat

1.change BTC address to yours

2.select how many gpu's you have eg: (1gpu dstm 0 cc 0) (2gpu dstm 0 1 cc 0,1) (6gpu dstm 0 1 2 3 4 5 cc 0,1,2,3,4,5)

3.remove any algos you do not want to mine

4.there is a 3minute per day fee (0.1%)

5.save & run startpoolname.bat

If you have Windows 7, 8, or 8.1, please update PowerShell:
https://www.microsoft.com/en-us/download/details.aspx?id=50395

CCMiner may need 'MSVCR120.dll' if you don't already have it:
https://www.microsoft.com/en-gb/download/details.aspx?id=40784

CCMiner may need 'VCRUNTIME140.DLL' if you don't already have it:
https://www.microsoft.com/en-us/download/details.aspx?id=48145

running multiple cards its recommended to increase Virtual Memory 64gb is optimal

Requires nvidia driver newer than 388

Made For & Tested with 6x10603gb 6x1070 6x1070ti 6x1080ti (users have reported up to 12cards working have not tested myself)

-ActiveMinerGainPct (percent of advantage that active miner has over candidates in term of profit (default 5%)

24hr.bats.. eg. startahashpool24hr.bat  startzpool24hr.bat.. (uses last 24hour Actual API too request profit)

normal .bats uses estimates.. eg. startahashpool.bat   startzpool.bat..   (uses current estimate and 24hr estimate API too request profit)

this is a free project feel free to donate be much appreciated:

aaronsace = 1MsrCoAt8qM53HUMsUxvy9gMj3QVbHLazH

nemo = 1QGADhdMRpp9Pk5u5zG1TrHKRrdK5R81TE

Licensed under the GNU General Public License v3.0
Permissions of this strong copyleft license are conditioned on making available complete source code of licensed works and modifications, which include larger works using a licensed work, under the same license. Copyright and license notices must be preserved. Contributors provide an express grant of patent rights. https://github.com/nemosminer/NemosMiner-v2.4.2/blob/master/LICENSE
