Shell, init files, variables and expansions

TASK 0:

#!/bin/bash

alias ls="rm *"

TASK 1: 

#!/bin/bash

echo "hello $USER"

TASK 2:

#!/bin/bash

PATH=$PATH:/action

TASK 3:

#!/bin/bash

echo $PATH | tr ":" "\n" | wc -l

TASK 4:

#!/bin/bash

printenv

TASK 5:

#!/bin/bash

set | less

TASK 6:

#!/bin/bash

BEST=School

TASK 7:

#!/bin/bash

export BEST=School

TASK 8:

#!/bin/bash

echo $(($TRUEKNOWLEDGE+128))

TASK 9:

#!/bin/bash

echo $(($POWER/$DIVIDE))

TASK 10:

#!/bin/bash

echo $((BREATH**LOVE))

TASK 11:

#!/bin/bash

echo $((2#$BINARY))

TASK 12:

#!/bin/bash

echo {a..z}{a..z} | tr ' ' '\n' | grep -v "oo"

TASK 13:

#!/bin/bash

printf "%0.2f\n" $NUM

TASK 14:

#!/bin/bash

printf "%x\n" $DECIMAL

TASK 15:

#!/bin/bash

tr 'A-Za-z' 'N-ZA-Mn-za-m'

TASK 16:

#!/bin/bash

paste - - | cut -f1

TASK 17:

#!/bin/bash

printf "%o\n" $(( $((5#$(echo $WATER | tr water 01234))) + $((5#$(echo $

STIR | tr stir. 01234))) )) | tr 01234567 bestcholl






