# fix bootstrap-select with jquery-steps
fix bootstrap-select's disappearance if you put it inside jQuery-steps

## to fix that add this css code :

        body {
            overflow-x: hidden;
        }

        .wizard>.content,
        .wizard {
            overflow: unset;
        }
