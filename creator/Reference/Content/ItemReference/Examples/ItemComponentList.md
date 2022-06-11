---
author: v-josjones
ms.author: v-josjones
title: Item Documentation - Item Component List
ms.prod: gaming
---

# 物品文档 - 物品组件

下方是所有可以用来编写物品json文件的组件列表.

>[重要提示]
> 物品组件要求打开 Holiday Creator Features 实验性功能.
>
>Holiday Creator Features 包含游戏实验性功能. 跟所有的实验性功能一样，你可以随意修改增加和删除都不会使得启动器警告。
>
>如果你想了解更多实验性功能，请访问 [Experimental Features in Minecraft: Bedrock Edition](../../../../../Documents/ExperimentalFeaturesToggle.md)


|键 |默认值  |类型  |说明  |
|:----------|:----------|:----------|:----------|
|[minecraft:armor](ItemComponents/minecraft_armor.md)|*未设置* |  JSON Object| 盔甲组件，可以定义盔甲的护甲量。 |
|[minecraft:block_placer](ItemComponents/minecraft_block_placer.md)|*未设置* | JSON Object| 种植组件。 种植物品可以像小麦一样种在耕地上。 |
|[minecraft:cooldown](ItemComponents/minecraft_cooldown.md)|*未设置* | JSON Object| 冷却时间组件。 在你使用一个物品后，它会在组件中的“cool down time”时间内无法再次使用。 |
|[minecraft:digger](ItemComponents/minecraft_digger.md)|*未设置* | JSON Object| 挖掘组件。 |
|[minecraft:display_name](ItemComponents/minecraft_display_name.md)|*未设置* | JSON Object| 显示物品名称组件。 显示物品的名字。 |
|[minecraft:durability](ItemComponents/minecraft_durability.md)|*未设置* |JSON Object| 耐久度组件：在损坏之前物品能够承受多少伤害。 |
|[minecraft:dye_powder](ItemComponents/minecraft_dye_powder.md)|*未设置* | JSON Object| 染料组件。目前有16种。 |
|[minecraft:entity_placer](ItemComponents/minecraft_entity_placer.md)|*未设置* | JSON Object| 实体放置组件。可以限制物品放置到允许的方块上。 |
|[minecraft:food](ItemComponents/minecraft_food.md)|*未设置* | JSON Object| 食物组件。添加食物组件物品可以被玩家食用。 |
|[minecraft:fuel](ItemComponents/minecraft_fuel.md)|*未设置* |  JSON Object| 燃料组件。添加燃料组件物品可以放进熔炉当燃料。 |
|[minecraft:icon](ItemComponents/minecraft_icon.md)|*未设置* | JSON Object| 物体显示的图标。 |
|[minecraft:knockback_resistance](ItemComponents/minecraft_knockback_resistance.md)|*未设置*| JSON Object| 防击退组件。添加防击退组件后可以给物品添加防击退效果。 |
|[minecraft:on_use](ItemComponents/minecraft_on_use.md)|*未设置* | JSON Object| 添加该组件后，允许你在使用物品时添加事件，类似于监听事件。 |
|[minecraft:on_use_on](ItemComponents/minecraft_on_use_on.md)|*未设置*| JSON Object | 添加该组件后，允许你在将物品放置到方块上添加事件。 |
|[minecraft:projectile](ItemComponents/minecraft_projectile.md)|*未设置* | JSON Object| 弹射物品组件。添加组件后物品可以像箭一样被射出。 |
|[minecraft:render_offsets](ItemComponents/minecraft_render_offsets.md)|*未设置* | JSON Object| 渲染偏移组件: 给出可选值来改变物品的渲染方式。 |
|[minecraft:repairable](ItemComponents/minecraft_repairable.md)|*未设置* | JSON Object| 修复组件。该物品是否可以被修复以及哪些东西可以修复它。 |
|[minecraft:shooter](ItemComponents/minecraft_shooter.md)|*未设置* | JSON Object| 射手组件。 |
|[minecraft:throwable](ItemComponents/minecraft_throwable.md)|*未设置* | JSON Object| 可投掷组件。像雪球一样可以投掷的物品。 |
|[minecraft:weapon](ItemComponents/minecraft_weapon.md)|*未设置* |  JSON Object| 武器组件。给所有武器添加的组件，例如剑，三叉戟等都添加了该组件。 |
|[minecraft:wearable](ItemComponents/minecraft_wearable.md)|*未设置* | JSON Object| 可穿戴物品组件。 |
