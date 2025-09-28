# Contributing to wiki.tamilnadu.tech

We welcome contributions from developers, designers, educators, and Tamil language enthusiasts.
If you're passionate about Tamil tech — your help makes a difference!

### 🔧 How to Contribute

1. **Fork** this repository
2. **Create a new branch** for your changes
3. **Add your resource or fix**
4. **Submit a Pull Request** with a descriptive message

### Adding a new resource

To add a new resource, you need to edit the `data.yml` file. Each resource is a YAML object with the following fields:

*   `name`: The name of the resource.
*   `description`: A brief description of the resource.
*   `url`: The URL of the resource.
*   `categories`: A list of categories the resource belongs to. The possible categories are:
    *   `Code`: Tamil-focused libraries and source code repositories
    *   `Dictionaries`: Bilingual tools, Tamil thesauri, and lexical data
    *   `Fonts`: Unicode-compliant Tamil fonts and input tools
    *   `Resources`: Datasets, corpora, digitized texts, cultural archives
    *   `Tools`: Transliteration, text processors, converters, analyzers
*   `device`: A list of devices the resource is available on. The possible values are:
    *   `Web`
    *   `Windows`
    *   `Mac`
    *   `Linux`
    *   `Mobile`

Here is an example of a resource entry:

```yaml
- name: "Tamilnadu.tech"
  description: "Directory of Tech Event happening in Tamil Nadu."
  url: "https://tamilnadu.tech"
  categories: [Resources]
  device: [Web]
```

### ✅ Contribution Guidelines

| Type         | Notes                                                                  |
| ------------ | ---------------------------------------------------------------------- |
| UI Changes   | Include a screenshot or preview of your update                         |
| Bug Fixes    | Describe the issue and how your fix resolves it                        |
| New Features | Provide context, expected behavior, and optionally a mockup            |
| Data Updates | Follow the `data.yml` format; update allowed hostnames if needed |
