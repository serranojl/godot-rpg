# Devlogs

> June 29. 2022

1. Added player attack animation
   - AnimationNodeStateMachine
     - Attack
2. Added player attack script
3. Added track method to player attack animations (Key: attack_animation_finished())
   - Animations
     - AttackDown
     - AttakLeft
     - AttackRight
     - AttackUp
4. Added Grass Scene
   - instance a GrassEffect scene
     - add grassEffect instance to world tree scene
     - set grassEffect global position to grass position
5. Added GrassEffect Scene
   - AnimatedSprite
     - add animation_finished() signal to GrassEffect

> June 26, 2022

1. Added new animations to player scene
   - animations
     - AttackDown
     - AttackLeft
     - AttackRight
     - AttackUp
     - RollDown
     - RollLeft
     - RollRight
     - RollUp
2. Added custom input map keys
   - move_down
   - move_left
   - move_right
   - move_up
3. Added player movements
4. Added player movement animation
   - AnimationNodeStateMachine
     - Idle
     - Run
5. Added world scene
6. Added bush scene
7. Updated Ysort on the world scene
8. Added background sprite on world scene
9. Added dirt path tile map
   - Autotile
     - step x = 16 y = 16
     - selected tiles subtile size x = 16 y = 16
     - autotile bitmask = 3x3 minimal
10. Added dirt cliff tile map
    - Autotile
      - step x = 32 y = 32
      - selected tiles subtile size x = 32 y = 32
      - autotile bitmask = 3x3 minimal


> June 25, 2022

1. Created github godot-rpg repository
2. Setup github account on windows pc
3. Setup gpg keys on git bash
4. Created godot rpg project
5. Pull git godot-rpg repository
6. Updated import settings on godot
   - set the filter flag to off
   - change presets to 2D Pixels
7. Updated project settings window display
   - width 320
   - height 180
   - test height and test width (monitor display size)
   - strech mode 2D
8. Added player scene
   - sprite animation
     - 60 Hframes
9. Added AnimationPlayer node to player scene
   - animations
     - IdleDown
     - IdleLeft
     - IdleRight
     - IdleUp
     - RunDown
     - RunLeft
     - RunRight
     - RunUp 
