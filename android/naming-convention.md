## Naming files

### Class files

| Component        | Class name             |
| ---------------- | ---------------------- | 
| Activity         | `LoginActivity`        |
| Fragment         | `LoginFragment`        |
| Dialog           | `LoginDialog`        |

### Resources files <Resources>

#### Layout

| Component        | Class name             | Layout name                 |
| ---------------- | ---------------------- | ----------------------------- |
| Activity         | `LoginActivity`        | `activity_login.xml`   |
| Fragment         | `LoginFragment`        | `fragment_login.xml`        |
| Dialog           | `LoginDialog`          | `dialog_login.xml`  |
| AdapterView item | ---                    | `item_person.xml`             |
| Partial layout   | ---                    | `layout_header.xml`       |

Naming id


#### Drawable files

Naming Drawables:

| Type   | Prefix            |		Example               |
|--------------| ------------------|-----------------------------|
| Action bar   | `ab_`             | `ab_stacked.9.png`          |
| Button       | `btn_`	            | `btn_send_pressed.9.png`    |
| Dialog       | `dialog_`         | `dialog_top.9.png`          | 
| Divider      | `divider_`        | `divider_horizontal.9.png`  |
| Icon         | `ic_`	            | `ic_star.png`               |
| Menu         | `menu_	`           | `menu_submenu_bg.9.png`     |
| Notification | `notification_`	| `notification_bg.9.png`     |
| Tabs         | `tab_`            | `tab_pressed.9.png`         |

Naming Icon ([Android iconography guidelines](http://developer.android.com/design/style/iconography.html)):

| Type                      | Prefix       | Example                     |
| --------------------------------| ----------------   | ---------------------------- | 
| Icons                           | `ic_`              | `ic_star.png`                |
| Launcher icons                  | `ic_launcher`      | `ic_launcher_calendar.png`   |
| Menu icons and Action Bar icons | `ic_menu`          | `ic_menu_archive.png`        |
| Status bar icons                | `ic_stat_notify`   | `ic_stat_notify_msg.png`     |
| Tab icons                       | `ic_tab`           | `ic_tab_recent.png`          |
| Dialog icons                    | `ic_dialog`        | `ic_dialog_info.png`         |

Naming selector states:

| State	       | Suffix     | Example                     |
|--------------|-----------------|-----------------------------|
| Normal       | `_normal`       | `btn_order_normal.9.png`    |
| Pressed      | `_pressed`      | `btn_order_pressed.9.png`   |
| Focused      | `_focused`      | `btn_order_focused.9.png`   |
| Disabled     | `_disabled`     | `btn_order_disabled.9.png`  |
| Selected     | `_selected`     | `btn_order_selected.9.png`  |

#### String
```
<string name="login">Login</string>
```
I think we should name it like this for support multiple language easier and easy to reuse in many
 screen without thinking about how to name

#### Dimen
```
<string name="dp_60">60dp</string>
<string name="sp_60">60sp</string>
```
Should name like this to prevent create too many dimens with same value.  
If we want to make something that reusable and easy to change then we should use style

### Color
```
<color name="red">#f00</string>
```
Should name like this to prevent create too many color with same value.  
If we want to make something that reusable and easy to change then we should use style


