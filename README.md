# 获取物品
## 🍞 一、常见食物（可食用恢复体力）

| 名称                    | 指令                    |
| --------------------- | --------------------- |
| 披萨（Pizza）             | `player_add (O)206 5` |
| 沙拉（Salad）             | `player_add (O)196 5` |
| 煎蛋（Fried Egg）         | `player_add (O)194 5` |
| 炒蛋（Omelet）            | `player_add (O)195 5` |
| 面包（Bread）             | `player_add (O)216 5` |
| 意大利面（Spaghetti）       | `player_add (O)194 5` |
| 巧克力蛋糕（Chocolate Cake） | `player_add (O)220 5` |
| 粉红蛋糕（Pink Cake）       | `player_add (O)221 5` |
| 咖喱饭（Curry）            | `player_add (O)921 5` |
| 冰激凌（Ice Cream）        | `player_add (O)233 5` |
| 鱼肉卷（Fish Taco）        | `player_add (O)213 5` |
| 南瓜汤（Pumpkin Soup）     | `player_add (O)236 5` |
| 蛋炒饭（Fried Rice）       | `player_add (O)198 5` |
| 龙虾晚餐（Lobster Dinner）  | `player_add (O)732 5` |

---

## ☕ 二、常见饮品

| 名称              | 指令                    |
| --------------- | --------------------- |
| 咖啡（Coffee）      | `player_add (O)395 5` |
| 啤酒（Beer）        | `player_add (O)346 5` |
| 葡萄酒（Wine）       | `player_add (O)348 5` |
| 绿茶（Green Tea）   | `player_add (O)614 5` |
| 蜂蜜酒（Mead）       | `player_add (O)459 5` |
| 果汁（Juice）       | `player_add (O)350 5` |
| 牛奶（Milk）        | `player_add (O)184 5` |
| 大牛奶（Large Milk） | `player_add (O)186 5` |

---

## 🛠️ 三、常用工具

| 名称                   | 指令                             |
| -------------------- | ------------------------------ |
| 镐（Pickaxe）           | `player_add (T)Pickaxe`        |
| 铜镐（Copper Pickaxe）   | `player_add (T)CopperPickaxe`  |
| 金镐（Gold Pickaxe）     | `player_add (T)GoldPickaxe`    |
| 铱镐（Iridium Pickaxe）  | `player_add (T)IridiumPickaxe` |
| 斧头（Axe）              | `player_add (T)Axe`            |
| 铲子（Hoe）              | `player_add (T)Hoe`            |
| 水壶（Watering Can）     | `player_add (T)WateringCan`    |
| 金锅（Gold Pan）         | `player_add (T)GoldPan`        |
| 牛奶桶（Milk Pail）       | `player_add (T)MilkPail`       |
| 剪刀（Shears）           | `player_add (T)Shears`         |
| 回程权杖（Return Scepter） | `player_add (T)ReturnScepter`  |

---

## 👕 四、衣服（Shirts）

| 名称                       | 指令                   |
| ------------------------ | -------------------- |
| 绿色外套（Green Jacket Shirt） | `player_add (S)1270` |
| 红色连帽衫（Red Hoodie）        | `player_add (S)1162` |
| 灰色连帽衫（Gray Hoodie）       | `player_add (S)1160` |
| 蓝色衬衫（Blue Shirt）         | `player_add (S)1003` |
| 礼服（Navy Tuxedo）          | `player_add (S)1185` |
| 工作服（Work Shirt）          | `player_add (S)1029` |

---

## 🎩 五、帽子（Hats）

| 名称                  | 指令                 |
| ------------------- | ------------------ |
| 草帽（Straw Hat）       | `player_add (H)4`  |
| 牛仔帽（Cowboy Hat）     | `player_add (H)2`  |
| 礼帽（Top Hat）         | `player_add (H)20` |
| 红头巾（Red Cap）        | `player_add (H)9`  |
| 维京头盔（Viking Helmet） | `player_add (H)45` |

---

## 👢 六、鞋子（Boots）

| 名称                 | 指令                  |
| ------------------ | ------------------- |
| 皮靴（Leather Boots）  | `player_add (B)504` |
| 竹靴（Rubber Boots）   | `player_add (B)505` |
| 火山靴（Volcano Boots） | `player_add (B)853` |
| 铱靴（Iridium Boots）  | `player_add (B)854` |
| 战斗靴（Combat Boots）  | `player_add (B)509` |

---

### 🧭 提示

* 若想查看某类物品，可输入：

  ```
  list_items food
  list_items drink
  list_items tool
  list_items shirt
  list_items hat
  list_items boots
  ```
* 控制台支持模糊搜索，例如：

  ```
  list_items cake
  list_items beer
  list_items pickaxe
  ```

---

# 更新状态
```
player_sethealth 100
player_setstamina 270
player_setmoney 9999999
```