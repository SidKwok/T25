<template>
    <div class="hello">
        <h1 class="shake-rotate">{{ msg }}</h1>
    </div>
</template>

<script>
export default {
    name: 'hello',
    data() {
        return {
            msg: 'T25'
        }
    }
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h1 {
  font-weight: normal;
  font-style: italic;
  font-size: 48px;
}

ul {
  list-style-type: none;
  padding: 0;
}

li {
  display: inline-block;
  margin: 0 10px;
}

a {
  color: #42b983;
}

/**shake it off! shake it off!**/
.shake-rotate {
    display: inline-block;
    transform-origin: center center;
}

.shake-rotate:hover,
.shake-rotate {
    animation-play-state: running;
}

@keyframes shake-rotate {
    2% {
        transform: translate(0, 0) rotate(-4.5deg);
    }
    4% {
        transform: translate(0, 0) rotate(-3.5deg);
    }
    6% {
        transform: translate(0, 0) rotate(5.5deg);
    }
    8% {
        transform: translate(0, 0) rotate(-2.5deg);
    }
    10% {
        transform: translate(0, 0) rotate(0.5deg);
    }
    12% {
        transform: translate(0, 0) rotate(7.5deg);
    }
    14% {
        transform: translate(0, 0) rotate(-3.5deg);
    }
    16% {
        transform: translate(0, 0) rotate(-3.5deg);
    }
    18% {
        transform: translate(0, 0) rotate(1.5deg);
    }
    20% {
      transform: translate(0, 0) rotate(7.5deg);
  }
    22% {
        transform: translate(0, 0) rotate(-1.5deg);
    }
    24% {
        transform: translate(0, 0) rotate(-1.5deg);
    }
    26% {
        transform: translate(0, 0) rotate(6.5deg);
    }
    28% {
        transform: translate(0, 0) rotate(5.5deg);
    }
    30% {
        transform: translate(0, 0) rotate(-5.5deg);
    }
    32% {
        transform: translate(0, 0) rotate(-1.5deg);
    }
    34% {
        transform: translate(0, 0) rotate(-5.5deg);
    }
    36% {
        transform: translate(0, 0) rotate(-6.5deg);
    }
    38% {
        transform: translate(0, 0) rotate(6.5deg);
    }
    40% {
        transform: translate(0, 0) rotate(-2.5deg);
    }
    42% {
        transform: translate(0, 0) rotate(-4.5deg);
    }
    44% {
        transform: translate(0, 0) rotate(-2.5deg);
    }
    46% {
        transform: translate(0, 0) rotate(-5.5deg);
    }
    48% {
        transform: translate(0, 0) rotate(4.5deg);
    }
    50% {
        transform: translate(0, 0) rotate(1.5deg);
    }
    52% {
        transform: translate(0, 0) rotate(5.5deg);
    }
    54% {
        transform: translate(0, 0) rotate(-3.5deg);
    }
    56% {
        transform: translate(0, 0) rotate(-0.5deg);
    }
    58% {
        transform: translate(0, 0) rotate(5.5deg);
    }
    60% {
        transform: translate(0, 0) rotate(4.5deg);
    }
    62% {
        transform: translate(0, 0) rotate(-5.5deg);
    }
    64% {
        transform: translate(0, 0) rotate(6.5deg);
    }
    66% {
        transform: translate(0, 0) rotate(6.5deg);
    }
    68% {
        transform: translate(0, 0) rotate(0.5deg);
    }
    70% {
        transform: translate(0, 0) rotate(0.5deg);
    }
    72% {
        transform: translate(0, 0) rotate(-5.5deg);
    }
    74% {
        transform: translate(0, 0) rotate(2.5deg);
    }
    76% {
        transform: translate(0, 0) rotate(0.5deg);
    }
    78% {
        transform: translate(0, 0) rotate(6.5deg);
    }
    80% {
        transform: translate(0, 0) rotate(3.5deg);
    }
    82% {
        transform: translate(0, 0) rotate(0.5deg);
    }
    84% {
        transform: translate(0, 0) rotate(5.5deg);
    }
    86% {
        transform: translate(0, 0) rotate(-5.5deg);
    }
    88% {
        transform: translate(0, 0) rotate(2.5deg);
    }
    90% {
        transform: translate(0, 0) rotate(6.5deg);
    }
    92% {
        transform: translate(0, 0) rotate(-2.5deg);
    }
    94% {
        transform: translate(0, 0) rotate(6.5deg);
    }
    96% {
        transform: translate(0, 0) rotate(-5.5deg);
    }
    98% {
        transform: translate(0, 0) rotate(-1.5deg);
    }
    0%, 100% {
        transform: translate(0, 0) rotate(0);
    }
}

.shake-rotate:hover {
    animation-duration: 100ms;
    animation-iteration-count: infinite;
    animation-name: shake-rotate;
    animation-timing-function: ease-in-out;
}
</style>
