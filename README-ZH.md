# 中文文档

## 🌍 world-info-kit

**world-info-kit** 是一个综合性的数据包，包含全球的主要数据，例如语言、国家、时区、货币等。该数据包旨在为需要国际数据的应用程序提供简单易用的访问。

## 🌟 特性

- **语言**: 世界上主要的语言信息，包括英文和中文名称以及对应的国旗。
- **国家**: 提供国家的名称、首都、区域、次区域和国旗等信息。
- **时区**: 每个国家的时区信息，格式为 `UTC偏移`。
- **货币**: 提供货币的代码、名称和符号。
- **一周的开始**: 每个国家的周起始日（周一或周日）。

## 📦 安装

你可以通过以下命令安装这个包：

```bash
npm install world-info-kit
```

### 示例输出

```json
{
  "code": "eng",
  "name": "English",
  "flag": "https://flagcdn.com/gs.svg",
  "chinese": "英语",
  "capital": "King Edward Point",
  "region": "Antarctic",
  "subregion": "N/A",
  "timezones": [
    "UTC-02:00"
  ],
  "startOfWeek": "monday",
  "currency": {
    "code": "SHP",
    "name": "Saint Helena pound",
    "symbol": "£"
  }
}
```

## 🌍 数据内容

此数据包提供结构化的 JSON 数据，便于访问全球信息。以下是包含内容的详细说明：

### 1. **语言**

每个语言条目包括：
- **code**: 语言代码（ISO 639-1 标准）。
- **name**: 语言的英文名称。
- **chinese**: 语言的中文名称。
- **flag**: 对应国家国旗的 URL。

### 2. **国家**

每个国家条目包括：
- **code**: ISO Alpha-3 国家代码。
- **name**: 国家名称（英文）。
- **capital**: 首都。
- **region**: 地区（如非洲、欧洲）。
- **subregion**: 次区域（如果适用）。
- **flag**: 国家的国旗 URL。

### 3. **时区**

- 时区以 `UTC±hh:mm` 格式列出。

### 4. **货币**

每个货币条目包含：
- **code**: 官方货币代码（ISO 4217 标准）。
- **name**: 货币的全称。
- **symbol**: 货币符号（例如 $, €, £）。

### 5. **一周的开始**

- 指示每个国家的一周起始日（周一或周日）。

---

## 📝 许可证

本项目采用 MIT 许可证。更多信息请查看 [LICENSE](https://opensource.org/licenses/MIT) 文件。
```
