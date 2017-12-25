# JamaraRepository
Repository for the Jamara algorithm combat detection which works for minecraft versions from 1.8 to 1.12.

# Information
Jamara is a spigot plugin which recalculates and proceeds mathematical algorithms to ensure safe gameplay.
It proceeds defensive and offensive checks which will most likely return a reliable result.
Jamara does __not__ rely on heuristics or any other unsafe analysis.

# Internal
Jamaras internal-version works out of the box and like any other spigot plugin.
It only relies on __ProtocolLib__ , so if you expect good results make sure you have the latest version of __Jamara__ and __ProtoclLib__ installed inside your plugins folder.
Pros:
    -Fast and reliable results
    -Internal usage and monitoring
Contras:
    -Probable high CPU usage due to calculations

# External
Jamara will soon offer an external version which works over a __Adapter-Plugin__.
This method of using Jamara allows your server to acces the __Jamara servers__ over the __Jamara Adapter-Plugin__, and to proceed the calculations over these servers.
Pros:
    -Complete relief of your servers CPU while proceeding the results
Contras:
    -Delayed results due to the latency of your connection to the Jamara servers
    -Depends on external servers
    
    
# CPU and Configuration
Jamara does have configurables which allows the user to adjust Jamara in order to work in harmony with the server.
However, setting all configurable values to the maximum will unfortunately have impact on your CPU.
Further __configurations__ can be found in this repository.
