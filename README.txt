Data Structure Combined Platform v96
Base: v95

DLL current pointer fixes:
- current pointer aligned vertically with start at top: 8px
- setposition uses 0-based index consistently
- current starts at node 0
- each current = current.next step moves exactly one node to the right
- currentpos and currentIndex remain synchronized
- return step points to node[index] and reads data[index]
- fixed fallback setposition behavior
- passed node --check
