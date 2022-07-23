# .NET で VB 開発サンプル

##  作業メモ

- Step 1. ソリューションを新規作成

```
dotnet new sln --output Sample
```

- Step 2. プロジェクトファイルを新規作成

```
dotnet new winforms --target-framework-override net6.0  \
    --language VB  --output Sample/TestVB
```
