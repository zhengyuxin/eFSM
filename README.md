# eFSM
event Finite State Machine for Kubernetes
It's base stone of Event Based Analysis(EBA) for kubernetes health.  

## Visualize
Visualization of eFSM could be helpful for both verfication and debugging. Open source [GraphViz](http://www.graphviz.org/) library could be leveraged for this purpose. 

Install GraphViz on Mac
```bash
brew install Graphviz
```

Convert .dot language file expected by GraphViz using the visualize method
```bash
cd eFSMs
dot -Tpng simplePod_eFSM.dot  -o simplePod_eFSM.png; 
open simplePod_eFSM.png
```
