[English](README.md) | 日本語

![CHP](https://github.com/uma-channel/CommandHelperPlus/blob/main/logos/chp_logo.png)

### Command Helper Plus は、Minecraft のコマンド作業を快適にします。
### 痒い所に手が届く、必須級の便利 MOD です。

## バージョン対応状況
✅: 実装済み｜📝: 実装予定
| ローダー | バージョン | 実装状況 |
|---|---|---|
| Fabric | 1.20.4 | 📝 |
| Fabric | 1.21.10 | ✅ |
| Fabric | 1.21.11 | 📝 |
| Fabric | 26.3 | 📝 |

## 前提条件

- **Minecraft**: Java Edition
- **Modローダー**: Fabric
- **前提Mod**: [Fabric API](https://modrinth.com/mod/fabric-api/versions?c=release)
- **推奨Mod**: [ModMenu](https://modrinth.com/mod/modmenu/versions?c=release&l=fabric)

## ビルド方法

### MOD をビルド
```
./gradlew build
```

### 開発用クライアントを起動
```
./gradlew runClient
```

### 開発用サーバーを起動
```
./gradlew runServer
```

## Node.js ブリッジのセットアップ

```bash
cd node-bridge
npm install
```

## ライセンス

詳細は [LICENSE](LICENSE) を参照。
