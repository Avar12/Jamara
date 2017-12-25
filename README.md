# JamaraRepository
Repository for the Jamara algorithm combat detection which works for minecraft versions from 1.8 to 1.12.

# Information
Jamara is an spigot plugin which recalculates and proceeds mathematical algorithms to ensure safe gameplay.
It proceeds defensive and offensive checks which will most likely return a reliable result.
Jamara does __not__ rely on heuristics or any other unsafe analysis.

# Internal
Jamaras internal-version works out of the box and like any other spigot plugin.
It only relies on __ProtocolLib__ , so if you expect good results make sure you have the latest version of __Jamara__ and __ProtoclLib__ installed and in your plugins folder.
Pros:
    -Fast and reliable results
    -Internal usage and monitoring
Contras:
    -Probable high CPU usage due to calculations

# External
Jamara will soon offer a external version which works over a __Adapter-Plugin__.
This method of using Jamara allows your server to acces the __Jamara servers__ over the __Jamara Adapter-Plugin__, and to proceess the calculations over these servers.
Pros:
    -Complete relief of your servers CPU while processing the results
Contras:
    -Delayed results due to the packet latency of your connection to the Jamara servers
    -Dependent of external servers
    
    
# CPU and Configuration
Jamara does have configurations which allow the specific user to adjust Jamara in order to work in harmony with the server.
However, settingg all configurable values to the maximum will pretty surely have impact on your CPU.
Further __configurations__ can be found in this repository.
