### InterfaceByName

```golang
package main

import (
        "fmt"
        "net"
)

func main() {

        fmt.Println(net.InterfaceByName("ens33"))
}
```


go doc net  InterfaceByName

func InterfaceByName(name string) (*Interface, error)
    InterfaceByName returns the interface specified by name.

        
    
net.InterfaceByName 函数接受一个字符串 返回一个 结构指针




### NetworkLinkAddIp

go doc netlink  NetworkLinkAddIp

func NetworkLinkAddIp(iface *net.Interface, ip net.IP, ipNet *net.IPNet) error
    Add an Ip address to an interface. This is identical to: ip addr add
    $ip/$ipNet dev $iface








