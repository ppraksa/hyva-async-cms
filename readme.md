## Async CMS content (GraphQL)

### About

Project based on the Magento2 + Hyvä.

![Magento Logo](https://upload.wikimedia.org/wikipedia/commons/3/3f/Magento_Logo.svg)
![Hyvä Logo](https://hyva.io/assets/images/hyva-logo.svg)
![GraphQL Logo](https://upload.wikimedia.org/wikipedia/commons/1/17/GraphQL_Logo.svg)

Alpine.js + TailwindCSS + skeleton technique.

### Installation

1. Copy and paste the block `.phtml` file into your Magento theme's appropriate template directory.
2. Add this code in your parent block/container in the layout XML:

```xml
<block name="async_cms" as="async_cms" template="Vendor_Module::cms/async_block.phtml" />
```

3. In the layout XML, add the necessary configuration:

```xml
<arguments>
    <argument name="block_identifier" xsi:type="string">block_identifier</argument>
    <argument name="container_css_class" xsi:type="string">flex flex-col items-center gap-8</argument>
    <argument name="skeleton_length" xsi:type="number">10</argument>
</arguments>
```

4. It's done!

### Contributing

We welcome contributions! Please follow the [contribution guidelines](CONTRIBUTING.md).

### License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
