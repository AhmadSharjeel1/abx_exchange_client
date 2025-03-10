# ABX Exchange Client
A C++ client for interacting with the ABX Mock Exchange Server.

## Prerequisites
- C++ Compiler (GCC/Clang)
- CMake
- Boost.Asio Library
- JSON Library (nlohmann/json.hpp)

## Installation & Running
1. Clone the repository  
   ```sh
   git clone https://github.com/AhmadSharjeel1/abx_exchange_client.git
   cd abx_exchange_client


## for build this  
cmake -B build 
cmake --build build -jn
./abx_client


## Output
The client requests data from the ABX exchange server and stores it in stock_data.json.

