## Info
### Task
Add the ability to display a scoreboard to players with useful information. Add the ability for players to conveniently edit the scoreboard. Make it possible to disable the scoreboard if necessary.
<table style="width:100%; text-align:center;">
  <tr>
    <td><strong>Version</strong><br>2.0</td>
    <td><strong>Development date</strong><br>12.04.25</td>
    <td><strong>Is supported</strong><br>🟢</td>
  </tr>
</table>

## Scoreboard
On the first attempt, the player is assigned a default scoreboard
<p align="start">
 <img width="300" src="https://github.com/user-attachments/assets/741de07c-b06e-4425-9c15-2574af445361" alt="snake"/>
</p>

When using the command /sb, the scoreboard editing menu opens for the player
<p align="start">
 <img width="300" src="https://github.com/user-attachments/assets/e1658d23-072b-423a-a161-abb33f8733fe" alt="snake"/>
</p>

## Edit Scoreboard
Interactive editing of the scoreboard takes place via the keyboard, there is a hint at the bottom of the scoreboard about the keys used and their actions

<p align="start">
 <img width="300" src="https://github.com/user-attachments/assets/e6a5be19-1009-488e-b076-7962e194d1a8" alt="snake"/>
</p>

## Hide Scoreboard
To hide the scoreboard, you can use the button in the menu or use the /sb hide command

<p align="start">
 <img width="300" src="https://github.com/user-attachments/assets/9bd1eea5-d26e-4ec7-8cf7-e9aee0c34a82" alt="snake"/>
</p>

## Reset Scoreboard
Reset the scoreboard via the menu (reset requires confirmation)
<p align="start">
 <img width="300" src="https://github.com/user-attachments/assets/f2657675-1dce-4ec4-ae66-e3ae97a1abe1"/>
</p>

## Admin
Adding placeholders
### Example
```java
DEATHS("☠","Смертей","%statistic_deaths%","",Material.SKELETON_SKULL,NamedTextColor.AQUA,"Ваши смерти"),
```
### Editing Settings
```yaml
settings:
  #КД между перемещением команды по скорборду в режиме редактирования (в тиках)
  cooldown-between-swap-team: 2
```

