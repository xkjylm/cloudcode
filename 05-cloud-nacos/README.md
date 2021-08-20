# Ribbon负载均衡

## Ribbon负载均衡规则

- 规则接口是IRule
- 默认实现是ZoneAvoidanceRule，根据zone选择服务列表，然后轮询

## 负载均衡自定义方式

-代码方式：配置灵活，但修改时需要重新打包发布
-配置方式：直观，方便，无需重新打包发布，但是无法做全局配置

## 饥饿加载

-开启饥饿加载
-指定饥饿加载的微服务名称