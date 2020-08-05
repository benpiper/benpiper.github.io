<script type="text/javascript">
    window.heap=window.heap||[],heap.load=function(e,t){window.heap.appid=e,window.heap.config=t=t||{};var r=t.forceSSL||"https:"===document.location.protocol,a=document.createElement("script");a.type="text/javascript",a.async=!0,a.src=(r?"https:":"http:")+"//cdn.heapanalytics.com/js/heap-"+e+".js";var n=document.getElementsByTagName("script")[0];n.parentNode.insertBefore(a,n);for(var o=function(e){return function(){heap.push([e].concat(Array.prototype.slice.call(arguments,0)))}},p=["addEventProperties","addUserProperties","clearEventProperties","identify","resetIdentity","removeEventProperty","setEventProperties","track","unsetEventProperty"],c=0;c<p.length;c++)heap[p[c]]=o(p[c])}; heap.load("4152617445");
</script>
# Resources for the *CCNP Enterprise Certification Study Guide: Exam 350-401* by [Ben Piper](https://benpiper.com)

## [Course Exercise Files](https://github.com/benpiper/ccnp-encor)

## Updates
There are no updates at this time.

## Errata
To report errata, please [create an issue here](https://github.com/benpiper/benpiper.github.io/issues/new?assignees=&labels=&template=errata-template.md&title=%5BErrata%5D).

### Chapter 5
#### Page 156, Configuring OSPF> Authentication > Configuring Area Authentication

The `router ospf 1` command is missing from R1's configuration:

```
! Enable area 0 authentication using MD5
R1(config)router ospf 1
R1(config-router)#area 0 authentication message-digest
```
