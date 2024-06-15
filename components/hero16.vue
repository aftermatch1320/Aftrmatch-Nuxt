<template>
  <div class="thq-section-padding">
    <div class="hero16-max-width thq-section-max-width">
      <div class="hero16-column thq-section-padding">
        <h1 class="thq-heading-1 hero16-text">AfterMatch</h1>
        <h1 class="thq-heading-1 hero16-text1">{{ heading1 }}</h1>
        <p class="thq-body-large hero16-text2">{{ content1 }}</p>
        <div class="hero16-actions">
          <button class="thq-button-filled hero16-button">
            <span class="thq-body-small">{{ action1 }}</span>
          </button>
          <button class="thq-button-outline hero16-button1">
            <span class="thq-body-small">{{ action2 }}</span>
          </button>
        </div>
      </div>
      <div class="hero16-content">
        <div
          class="hero16-column-container thq-mask-image-vertical thq-animated-group-container-vertical"
        >
          <div class="thq-animated-group-vertical">
            <img
              :alt="image1Alt"
              :src="image1Src"
              class="hero16-placeholder-image thq-img-scale thq-img-ratio-1-1"
            />
            <img
              :alt="image2Alt"
              :src="image2Src"
              class="hero16-placeholder-image01 thq-img-scale thq-img-ratio-1-1"
            />
            <img
              :alt="image3Alt"
              :src="image3Src"
              class="hero16-placeholder-image02 thq-img-scale thq-img-ratio-1-1"
            />
          </div>
          <div class="thq-animated-group-vertical">
            <img
              :alt="image1Alt"
              :src="image1Src"
              class="hero16-placeholder-image03 thq-img-scale thq-img-ratio-1-1"
            />
            <img
              :alt="image2Alt"
              :src="image2Src"
              class="hero16-placeholder-image04 thq-img-scale thq-img-ratio-1-1"
            />
            <img
              :alt="image3Alt"
              :src="image3Src"
              class="hero16-placeholder-image05 thq-img-scale thq-img-ratio-1-1"
            />
          </div>
        </div>
        <div
          class="hero16-column-container1 thq-mask-image-vertical thq-animated-group-container-vertical"
        >
          <div class="thq-animated-group-vertical-reverse">
            <img
              :alt="image4Alt"
              :src="image4Src"
              class="hero16-placeholder-image06 thq-img-scale thq-img-ratio-1-1"
            />
            <img
              :alt="image5Alt"
              :src="image5Src"
              class="hero16-placeholder-image07 thq-img-scale thq-img-ratio-1-1"
            />
            <img
              :alt="image6Alt"
              :src="image6Src"
              class="hero16-placeholder-image08 thq-img-scale thq-img-ratio-1-1"
            />
          </div>
          <div class="thq-animated-group-vertical-reverse">
            <img
              :alt="image4Alt"
              :src="image4Src"
              class="hero16-placeholder-image09 thq-img-scale thq-img-ratio-1-1"
            />
            <img
              :alt="image5Alt"
              :src="image5Src"
              class="hero16-placeholder-image10 thq-img-scale thq-img-ratio-1-1"
            />
            <img
              :alt="image6Alt"
              :src="image6Src"
              class="hero16-placeholder-image11 thq-img-scale thq-img-ratio-1-1"
            />
          </div>
        </div>
      </div>
    </div>
    <div>
      <div class="hero16-container1">
        <DangerousHTML
          html="<style>
    @keyframes scroll-x {
      from {
        transform: translateX(0);
      }
      to {
        transform: translateX(calc(-100% - 16px));
      }
    }
  
    @keyframes scroll-y {
      from {
        transform: translateY(0);
      }
      to {
        transform: translateY(calc(-100% - 16px));
      }
    }
  </style>
  "
        ></DangerousHTML>
      </div>
    </div>
  </div>
</template>

<script>
import DangerousHTML from 'dangerous-html/dist/vue/lib.js'

export default {
  name: 'Hero16',
  props: {
    image6Alt: {
      type: String,
      default: 'Hero Image',
    },
    image1Src: {
      type: String,
      default:
        'https://images.unsplash.com/photo-1517816981644-e0e3de7743e5?crop=entropy&cs=tinysrgb&fit=max&fm=jpg&ixid=M3w5MTMyMXwwfDF8cmFuZG9tfHx8fHx8fHx8MTcxNzc3NTYxNHw&ixlib=rb-4.0.3&q=80&w=1080',
    },
    image7Src: {
      type: String,
      default:
        'https://images.unsplash.com/photo-1570218625390-ca3c081c2cfb?crop=entropy&cs=tinysrgb&fit=max&fm=jpg&ixid=M3w5MTMyMXwwfDF8cmFuZG9tfHx8fHx8fHx8MTcxNzc3NTg2M3w&ixlib=rb-4.0.3&q=80&w=1080',
    },
    action2: {
      type: String,
      default: 'Sign Up Now',
    },
    image2Alt: {
      type: String,
      default: 'Hero Image',
    },
    image4Src: {
      type: String,
      default:
        'https://images.unsplash.com/photo-1658963642269-0a36c9eb5d66?crop=entropy&cs=tinysrgb&fit=max&fm=jpg&ixid=M3w5MTMyMXwwfDF8cmFuZG9tfHx8fHx8fHx8MTcxNzc3NTg2Mnw&ixlib=rb-4.0.3&q=80&w=1080',
    },
    heading1: {
      type: String,
      default: 'Find Your Perfect Match',
    },
    image5Src: {
      type: String,
      default:
        'https://images.unsplash.com/photo-1472099645785-5658abf4ff4e?crop=entropy&cs=tinysrgb&fit=max&fm=jpg&ixid=M3w5MTMyMXwwfDF8cmFuZG9tfHx8fHx8fHx8MTcxNzc3NTg2M3w&ixlib=rb-4.0.3&q=80&w=1080',
    },
    image3Src: {
      type: String,
      default:
        'https://images.unsplash.com/photo-1467806757054-808649965a76?crop=entropy&cs=tinysrgb&fit=max&fm=jpg&ixid=M3w5MTMyMXwwfDF8cmFuZG9tfHx8fHx8fHx8MTcxNzc3NTg2Mnw&ixlib=rb-4.0.3&q=80&w=1080',
    },
    action1: {
      type: String,
      default: 'Learn More',
    },
    image3Alt: {
      type: String,
      default: 'Hero Image',
    },
    image2Src: {
      type: String,
      default:
        'https://images.unsplash.com/photo-1631500007471-bbc988d170aa?crop=entropy&cs=tinysrgb&fit=max&fm=jpg&ixid=M3w5MTMyMXwwfDF8cmFuZG9tfHx8fHx8fHx8MTcxNzc3NTg2Mnw&ixlib=rb-4.0.3&q=80&w=1080',
    },
    image1Alt: {
      type: String,
      default: 'Modern Dating Webapp',
    },
    image5Alt: {
      type: String,
      default: 'Hero Image',
    },
    image6Src: {
      type: String,
      default:
        'https://images.unsplash.com/photo-1455849318743-b2233052fcff?crop=entropy&cs=tinysrgb&fit=max&fm=jpg&ixid=M3w5MTMyMXwwfDF8cmFuZG9tfHx8fHx8fHx8MTcxNzc3NTg2M3w&ixlib=rb-4.0.3&q=80&w=1080',
    },
    content1: {
      type: String,
      default:
        'Join our modern dating webapp and discover meaningful connections with like-minded individuals.',
    },
    image4Alt: {
      type: String,
      default: 'Hero Image',
    },
  },
  components: {
    DangerousHTML,
  },
}
</script>

<style scoped>
.hero16-max-width {
  display: flex;
  align-items: center;
  flex-direction: row;
  justify-content: center;
}
.hero16-column {
  gap: var(--dl-space-space-oneandhalfunits);
  width: 50%;
  display: flex;
  align-items: flex-start;
  animation-name: fadeInLeft;
  flex-direction: column;
  animation-delay: 0s;
  justify-content: center;
  animation-duration: 300ms;
  animation-direction: normal;
  animation-iteration-count: 1;
  animation-timing-function: ease;
}
.hero16-actions {
  gap: var(--dl-space-space-unit);
  display: flex;
  align-items: flex-start;
}
.hero16-content {
  gap: var(--dl-space-space-unit);
  width: 50%;
  height: 900px;
  display: flex;
}
.hero16-column-container {
  width: 50%;
}
.hero16-placeholder-image {
  width: 100%;
  height: 400px;
}
.hero16-placeholder-image01 {
  width: 100%;
  height: 400px;
}
.hero16-placeholder-image02 {
  width: 100%;
  height: 400px;
}
.hero16-placeholder-image03 {
  width: 100%;
  height: 400px;
}
.hero16-placeholder-image04 {
  width: 100%;
  height: 400px;
}
.hero16-placeholder-image05 {
  width: 100%;
  height: 400px;
}
.hero16-column-container1 {
  width: 50%;
}
.hero16-placeholder-image06 {
  width: 100%;
  height: 400px;
}
.hero16-placeholder-image07 {
  width: 100%;
  height: 400px;
}
.hero16-placeholder-image08 {
  width: 100%;
  height: 400px;
}
.hero16-placeholder-image09 {
  width: 100%;
  height: 400px;
}
.hero16-placeholder-image10 {
  width: 100%;
  height: 400px;
}
.hero16-placeholder-image11 {
  width: 100%;
  height: 400px;
}
.hero16-container1 {
  display: contents;
}
@media(max-width: 991px) {
  .hero16-max-width {
    flex-direction: column;
  }
  .hero16-column {
    width: 100%;
    padding-left: var(--dl-space-space-fiveunits);
    padding-right: var(--dl-space-space-fiveunits);
  }
  .hero16-content {
    width: 100%;
    height: 100vh;
    justify-content: center;
  }
}
@media(max-width: 767px) {
  .hero16-column {
    padding-top: var(--dl-space-space-threeunits);
    padding-left: var(--dl-space-space-threeunits);
    padding-right: var(--dl-space-space-threeunits);
    padding-bottom: var(--dl-space-space-threeunits);
  }
  .hero16-text {
    text-align: center;
  }
  .hero16-text1 {
    text-align: center;
  }
  .hero16-text2 {
    text-align: center;
  }
  .hero16-actions {
    width: 100%;
    justify-content: center;
  }
}
@media(max-width: 479px) {
  .hero16-column {
    padding-top: var(--dl-space-space-oneandhalfunits);
    padding-left: var(--dl-space-space-oneandhalfunits);
    padding-right: var(--dl-space-space-oneandhalfunits);
  }
  .hero16-text {
    text-align: center;
  }
  .hero16-text1 {
    text-align: center;
  }
  .hero16-text2 {
    text-align: center;
  }
  .hero16-actions {
    flex-direction: column;
  }
  .hero16-button {
    width: 100%;
  }
  .hero16-button1 {
    width: 100%;
  }
}
</style>
