
# <p align="center">About The Project ✨</p>
  
This Garbage Collector is a tool that replaces 'free( )' and 'malloc( )', to allow you to liberate all allocations made all at once.


# <p align="center">Compilation 📝</p>
  
To use the Garbage Collector, you have to go inside the folder and compile it with 'make'.
Then compile the 'garbage_collector.a' with other C files to use it.
Don't forget to include 'garbage_collector.h'


# <p align="center">Usage ⚙️</p>

There are 3 functions in this library :

 - ft_malloc   : this function works like the real malloc function,  it returns a pointers to an heap allocated zone, of the size specified in parameter. Make sure to use this function at least one time before the others.

- ft_free : this function copy the real 'free( )' function. You can use it on all addresses, whether they are allocated by the 'ft_malloc( )' function or not.

- destroy_garbage : this function free the garbage and all the addresses allocated by 'ft_malloc( )' but not freed by 'ft_free( )'. Use it with a NULL parameter. Make sure to use this function at the very end, because the others functions are disabled after that.


## More . . . 😆

If you want to find more of my [projects](https://photo.capital.fr/musk-25050#the-boring-company-des-tunnels-pour-desengorger-le-trafic-en-ville-434177) .
        
        
    
