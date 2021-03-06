# Changelog

## 0.1.0
- Provide usable network programing models & extensible network filter extension framework
- Support protocol framework & sofa rpc implementation (tr/boltv1/boltv2)
- Support stream framework & http2 / sofa rpc stream & client & pool implementation
- Support stream filter extension framework & some filter implementation
- Support proxying http2 / sofa rpc request in a mesh way
- Support cluster management & lb strategies
- Integration with confreg in service discovery model
- Support basic route support
- Support start from a json-format config file
- Support HUP smooth reload
- Support process smooth upgrade
- Process guard by supervisord & log managed by logrotate
- More features...

## [0.2.0](docs/features/0.2.0/0-2-0-list.md)
- Support wrr loadbalancer
- Support weighted subset router
- Support listener update/delete, integrated with ISTIO pilot by XDS api
- Support cluster update/delete, integrated with ISTIO pilot by XDS api
- Support network filter extensions, allows config multiple filters
- Support TLS extension, allows customized certificate acquisition
- Support io callback mechanism based on raw epoll/kqueue, optimize support for a large number of connections through io worker pool
- Enhance customized codec extension mechanism in protocol layer
- Add first version of x-protocol extension mechanism
- Add memory reuse framework, use it in io/protocol/stream/protocol layers
- Fix data race cases
- Fix some bugs
