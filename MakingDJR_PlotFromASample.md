<par>Run the MadAnalysis in the hadron-level mode</par>
```bash
./bin/ma5 -H
import /home/camilo/cms/Scripts_MadGraph_VLFTEO/Datos/BackGround-tW/Events/run_01/tag_3_pythia8_events.hepmc.gz
set main.merging.check = true
set main.merging.njets = 4
#set main.lumi=0.01
submit merging_test
```
