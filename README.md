# Onion Conditions

Compose conditions like `playerLevel >= 5` in the inspector, on top of [Onion Variables](https://github.com/onion-unity/onion-variables).

```csharp
[SerializeField] Condition _canOpen;

if (_canOpen) Open();
```
