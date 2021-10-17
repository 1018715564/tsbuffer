<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [tsbuffer](./tsbuffer.md) &gt; [TSBufferOptions](./tsbuffer.tsbufferoptions.md) &gt; [excessPropertyChecks](./tsbuffer.tsbufferoptions.excesspropertychecks.md)

## TSBufferOptions.excessPropertyChecks property

检查值中是否包含Schema定义之外多余的字段 仅对 `validate` 方法生效 是因为实现机制原因, `prune` `encode` `decode` 方法都会天然保证不会混入多余字段

默认：`true`

<b>Signature:</b>

```typescript
excessPropertyChecks: boolean;
```