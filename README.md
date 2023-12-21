# NestJS Sequelize Snippets for VSCode Editor

[![Latest Release](https://img.shields.io/visual-studio-marketplace/v/imgildev.vscode-nestjs-sequelize-snippets?style=flat&label=VS%20Marketplace&logo=visual-studio-code)](https://marketplace.visualstudio.com/items?itemName=imgildev.vscode-nestjs-sequelize-snippets)
[![GitHub license](https://img.shields.io/github/license/ManuelGil/vscode-nestjs-sequelize-snippets)]()

This extension adds code snippets for Sequelize ORM for JavaScript and TypeScript in VS Code editor.

## Requirements

- VSCode 1.46.0 or later

## Usage

### Snippets

![demo](https://raw.githubusercontent.com/ManuelGil/vscode-nestjs-sequelize-snippets/main/docs/images/demo.gif)

Type part of snippet, press `Tab` or `Enter`, and the snippet unfolds. Below is a list of the most important shortcuts.

| Snippet | Purpose |
| --- | --- |
| ns_sequelize_deco_created_at | @CreatedAt public createdAt: Date; |
| ns_sequelize_deco_updated_at | @UpdatedAt public updatedAt: Date; |
| ns_sequelize_deco_deleted_at | @DeletedAt public deletedAt: Date; |
| ns_sequelize_deco_table | @Table() export class ... extends Model { ... } |
| ns_sequelize_deco_auto_increment | @AutoIncrement |
| ns_sequelize_deco_primary_key | @PrimaryKey |
| ns_sequelize_deco_index | @Index() |
| ns_sequelize_deco_column | @Column({ ... }) |
| ns_sequelize_deco_allow_null | @AllowNull() |
| ns_sequelize_deco_unique | @Unique() |
| ns_sequelize_deco_default | @Default() |
| ns_sequelize_deco_comment | @Comment() |
| ns_sequelize_deco_before_bulk_create | @BeforeBulkCreate public static ...() { ... } |
| ns_sequelize_deco_before_bulk_destroy | @BeforeBulkDestroy public static ...() { ... } |
| ns_sequelize_deco_before_bulk_update | @BeforeBulkUpdate public static ...() { ... } |
| ns_sequelize_deco_before_create | @BeforeCreate public static ...() { ... } |
| ns_sequelize_deco_before_destroy | @BeforeDestroy public static ...() { ... } |
| ns_sequelize_deco_before_save | @BeforeSave public static ...() { ... } |
| ns_sequelize_deco_before_update | @BeforeUpdate public static ...() { ... } |
| ns_sequelize_deco_before_upsert | @BeforeUpsert public static ...() { ... } |
| ns_sequelize_deco_before_validate | @BeforeValidate public static ...() { ... } |
| ns_sequelize_deco_after_bulk_create  | @AfterBulkCreate public static ...() { ... } |
| ns_sequelize_deco_after_bulk_destroy | @AfterBulkDestroy public static ...() { ... } |
| ns_sequelize_deco_after_bulk_update  | @AfterBulkUpdate public static ...() { ... } |
| ns_sequelize_deco_after_create | @AfterCreate public static ...() { ... } |
| ns_sequelize_deco_after_destroy  | @AfterDestroy public static ...() { ... } |
| ns_sequelize_deco_after_save | @AfterSave public static ...() { ... } |
| ns_sequelize_deco_after_update | @AfterUpdate public static ...() { ... } |
| ns_sequelize_deco_after_upsert | @AfterUpsert public static ...() { ... } |
| ns_sequelize_deco_after_validate | @AfterValidate public static ...() { ... } |
| ns_sequelize_deco_has_many | @HasMany(() => model) |
| ns_sequelize_deco_has_one | @HasOne(() => model) |
| ns_sequelize_deco_foreign_key | @ForeignKey(() => model) |
| ns_sequelize_belongs_to | @BelongsTo(() => model) |
| ns_sequelize_belongs_to_many | @BelongsToMany(() => model, (() => model)) |

## Other Extensions

- [NestJS File Generator for VSCode](https://marketplace.visualstudio.com/items?itemName=imgildev.vscode-nestjs-generator)
- [NestJS Snippets for VSCode Editor](https://marketplace.visualstudio.com/items?itemName=imgildev.vscode-nestjs-snippets-extension)
- [Angular File Generator for VSCode Editor](https://marketplace.visualstudio.com/items?itemName=imgildev.vscode-angular-generator)
- [React / NextJS / T3 Stack File Generator](https://marketplace.visualstudio.com/items?itemName=imgildev.vscode-nextjs-generator)
- [Nx / Angular / Nest / Next Essential Extension Pack](https://marketplace.visualstudio.com/items?itemName=imgildev.vscode-nx-pack)
- [CodeIgniter 4 Snippets for Visual Studio Code](https://marketplace.visualstudio.com/items?itemName=imgildev.vscode-codeigniter4-shield-snippets)
- [CodeIgniter 4 Spark for Visual Studio Code](https://marketplace.visualstudio.com/items?itemName=imgildev.vscode-codeigniter4-shield-spark)
- [Moodle Pack](https://marketplace.visualstudio.com/items?itemName=imgildev.vscode-moodle-snippets)
- [Mustache Template Engine - Snippets & Autocomplete](https://marketplace.visualstudio.com/items?itemName=imgildev.vscode-mustache-snippets)

## Changelog

See [CHANGELOG.md](./CHANGELOG.md)

## Authors

- **Manuel Gil** - _Owner_ - [ManuelGil](https://github.com/ManuelGil)

See also the list of [contributors](https://github.com/ManuelGil/vscode-nestjs-sequelize-snippets/contributors) who participated in this project.

## License

NestJS Sequelize Snippets for VSCode is licensed under the MIT License - see the [MIT License](https://opensource.org/licenses/MIT) for details.
