<template>
  <div class="hero17-header78">
    <div class="hero17-column thq-section-padding thq-section-max-width">
      <div class="hero17-content">
        <h1 class="hero17-text thq-heading-1">{{ heading1 }}</h1>
        <p class="hero17-text1 thq-body-large">{{ content1 }}</p>
      </div>
      <div class="hero17-actions">
        <button class="thq-button-filled hero17-button">
          <span class="thq-body-small">{{ action1 }}</span>
        </button>
        <button class="thq-button-outline hero17-button1">
          <span class="thq-body-small">{{ action2 }}</span>
        </button>
      </div>
    </div>
    <div class="hero17-content1">
      <div
        class="hero17-row-container thq-mask-image-horizontal thq-animated-group-container-horizontal"
      >
        <div class="thq-animated-group-horizontal">
          <img
            :alt="image1Alt"
            :src="image1Src"
            class="hero17-placeholder-image thq-img-scale thq-img-ratio-1-1"
          />
          <img
            :alt="image2Alt"
            :src="image2Src"
            class="hero17-placeholder-image01 thq-img-scale thq-img-ratio-1-1"
          />
          <img
            :alt="image3Alt"
            :src="image3Src"
            class="hero17-placeholder-image02 thq-img-scale thq-img-ratio-1-1"
          />
          <img
            :alt="image4Alt"
            :src="image4Src"
            class="hero17-placeholder-image03 thq-img-scale thq-img-ratio-1-1"
          />
          <img
            :alt="image5Alt"
            :src="image5Src"
            class="hero17-placeholder-image04 thq-img-scale thq-img-ratio-1-1"
          />
          <img
            :alt="image6Alt"
            :src="image6Src"
            class="hero17-placeholder-image05 thq-img-scale thq-img-ratio-1-1"
          />
        </div>
        <div class="thq-animated-group-horizontal">
          <img
            :alt="image1Alt"
            :src="image1Src"
            class="hero17-placeholder-image06 thq-img-scale thq-img-ratio-1-1"
          />
          <img
            :alt="image2Alt"
            :src="image2Src"
            class="hero17-placeholder-image07 thq-img-scale thq-img-ratio-1-1"
          />
          <img
            :alt="image3Alt"
            :src="image3Src"
            class="hero17-placeholder-image08 thq-img-scale thq-img-ratio-1-1"
          />
          <img
            :alt="image4Alt"
            :src="image4Src"
            class="hero17-placeholder-image09 thq-img-scale thq-img-ratio-1-1"
          />
          <img
            :alt="image5Alt"
            :src="image5Src"
            class="hero17-placeholder-image10 thq-img-scale thq-img-ratio-1-1"
          />
          <img
            alt="Hero Image"
            src="https://images.unsplash.com/photo-1534312527009-56c7016453e6?ixid=M3w5MTMyMXwwfDF8c2VhcmNofDIxfHxhYnN0cmFjdHxlbnwwfHx8fDE3MTA4NzA5MzB8MA&amp;ixlib=rb-4.0.3&amp;w=1500"
            class="hero17-placeholder-image11 thq-img-scale thq-img-ratio-1-1"
          />
        </div>
      </div>
      <div
        class="hero17-row-container1 thq-mask-image-horizontal thq-animated-group-container-horizontal"
      >
        <div class="thq-animated-group-horizontal-reverse">
          <img
            :alt="image7Alt"
            :src="image7Src"
            class="hero17-placeholder-image12 thq-img-scale thq-img-ratio-1-1"
          />
          <img
            :alt="image8Alt"
            :src="image8Src"
            class="hero17-placeholder-image13 thq-img-scale thq-img-ratio-1-1"
          />
          <img
            :alt="image9Alt"
            :src="image9Src"
            class="hero17-placeholder-image14 thq-img-scale thq-img-ratio-1-1"
          />
          <img
            :alt="image10Alt"
            :src="image10Src"
            class="hero17-placeholder-image15 thq-img-scale thq-img-ratio-1-1"
          />
          <img
            :alt="image11Alt"
            :src="image11Src"
            class="hero17-placeholder-image16 thq-img-scale thq-img-ratio-1-1"
          />
          <img
            :alt="image12Alt"
            :src="image12Src"
            class="hero17-placeholder-image17 thq-img-scale thq-img-ratio-1-1"
          />
        </div>
        <div class="thq-animated-group-horizontal-reverse">
          <img
            :alt="image7Alt"
            :src="image7Src"
            class="hero17-placeholder-image18 thq-img-scale thq-img-ratio-1-1"
          />
          <img
            :alt="image8Alt"
            :src="image8Src"
            class="hero17-placeholder-image19 thq-img-scale thq-img-ratio-1-1"
          />
          <img
            :alt="image9Alt"
            :src="image9Src"
            class="hero17-placeholder-image20 thq-img-scale thq-img-ratio-1-1"
          />
          <img
            :alt="image10Alt"
            :src="image10Src"
            class="hero17-placeholder-image21 thq-img-scale thq-img-ratio-1-1"
          />
          <img
            :alt="image11Alt"
            :src="image11Src"
            class="hero17-placeholder-image22 thq-img-scale thq-img-ratio-1-1"
          />
          <img
            alt="Hero Image"
            src="https://images.unsplash.com/photo-1568214379698-8aeb8c6c6ac8?ixid=M3w5MTMyMXwwfDF8c2VhcmNofDEyfHxncmFmaWN8ZW58MHx8fHwxNzE1Nzk0OTk5fDA&amp;ixlib=rb-4.0.3&amp;w=1500"
            class="hero17-placeholder-image23 thq-img-scale thq-img-ratio-1-1"
          />
        </div>
      </div>
    </div>
    <div>
      <div class="hero17-container1">
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
  name: 'Hero17',
  props: {
    image12Alt: {
      type: String,
      default: 'Hero Image',
    },
    heading1: {
      type: String,
      default: 'Find Your Perfect Match',
    },
    image12Src: {
      type: String,
      default:
        'https://images.unsplash.com/photo-1717444308695-cacce29f6991?crop=entropy&cs=tinysrgb&fit=max&fm=jpg&ixid=M3w5MTMyMXwwfDF8cmFuZG9tfHx8fHx8fHx8MTcxNzc3NjgyN3w&ixlib=rb-4.0.3&q=80&w=1080',
    },
    image4Src: {
      type: String,
      default:
        'https://images.unsplash.com/photo-1658963642269-0a36c9eb5d66?crop=entropy&cs=tinysrgb&fit=max&fm=jpg&ixid=M3w5MTMyMXwwfDF8cmFuZG9tfHx8fHx8fHx8MTcxNzc3NTg2Mnw&ixlib=rb-4.0.3&q=80&w=1080',
    },
    action2: {
      type: String,
      default: 'Sign Up Now',
    },
    image2Alt: {
      type: String,
      default: 'Hero Image',
    },
    image9Src: {
      type: String,
      default:
        'https://images.unsplash.com/photo-1534528741775-53994a69daeb?crop=entropy&cs=tinysrgb&fit=max&fm=jpg&ixid=M3w5MTMyMXwwfDF8cmFuZG9tfHx8fHx8fHx8MTcxNzc3NjgyN3w&ixlib=rb-4.0.3&q=80&w=1080',
    },
    image7Alt: {
      type: String,
      default: 'Hero Image',
    },
    image8Src: {
      type: String,
      default:
        'https://images.unsplash.com/photo-1611262588019-db6cc2032da3?crop=entropy&cs=tinysrgb&fit=max&fm=jpg&ixid=M3w5MTMyMXwwfDF8cmFuZG9tfHx8fHx8fHx8MTcxNzc3NjgyOHw&ixlib=rb-4.0.3&q=80&w=1080',
    },
    image10Src: {
      type: String,
      default:
        'https://images.unsplash.com/photo-1631617945663-bc6a0f22834e?crop=entropy&cs=tinysrgb&fit=max&fm=jpg&ixid=M3w5MTMyMXwwfDF8cmFuZG9tfHx8fHx8fHx8MTcxNzc3NjgyOHw&ixlib=rb-4.0.3&q=80&w=1080',
    },
    image6Src: {
      type: String,
      default:
        'https://images.unsplash.com/photo-1455849318743-b2233052fcff?crop=entropy&cs=tinysrgb&fit=max&fm=jpg&ixid=M3w5MTMyMXwwfDF8cmFuZG9tfHx8fHx8fHx8MTcxNzc3NTg2M3w&ixlib=rb-4.0.3&q=80&w=1080',
    },
    image11Src: {
      type: String,
      default:
        'https://images.unsplash.com/photo-1611631645709-69a8c5f41358?crop=entropy&cs=tinysrgb&fit=max&fm=jpg&ixid=M3w5MTMyMXwwfDF8cmFuZG9tfHx8fHx8fHx8MTcxNzc3NjgyN3w&ixlib=rb-4.0.3&q=80&w=1080',
    },
    image5Alt: {
      type: String,
      default: 'Hero Image',
    },
    image6Alt: {
      type: String,
      default: 'Hero Image',
    },
    action1: {
      type: String,
      default: 'Learn More',
    },
    content1: {
      type: String,
      default:
        'Join our modern dating webapp and discover meaningful connections with like-minded individuals.',
    },
    image2Src: {
      type: String,
      default:
        'https://images.unsplash.com/photo-1631500007471-bbc988d170aa?crop=entropy&cs=tinysrgb&fit=max&fm=jpg&ixid=M3w5MTMyMXwwfDF8cmFuZG9tfHx8fHx8fHx8MTcxNzc3NTg2Mnw&ixlib=rb-4.0.3&q=80&w=1080',
    },
    image5Src: {
      type: String,
      default:
        'https://images.unsplash.com/photo-1472099645785-5658abf4ff4e?crop=entropy&cs=tinysrgb&fit=max&fm=jpg&ixid=M3w5MTMyMXwwfDF8cmFuZG9tfHx8fHx8fHx8MTcxNzc3NTg2M3w&ixlib=rb-4.0.3&q=80&w=1080',
    },
    image1Src: {
      type: String,
      default:
        'https://images.unsplash.com/photo-1517816981644-e0e3de7743e5?crop=entropy&cs=tinysrgb&fit=max&fm=jpg&ixid=M3w5MTMyMXwwfDF8cmFuZG9tfHx8fHx8fHx8MTcxNzc3NTYxNHw&ixlib=rb-4.0.3&q=80&w=1080',
    },
    image9Alt: {
      type: String,
      default: 'Hero Image',
    },
    image7Src: {
      type: String,
      default:
        'https://images.unsplash.com/photo-1570218625390-ca3c081c2cfb?crop=entropy&cs=tinysrgb&fit=max&fm=jpg&ixid=M3w5MTMyMXwwfDF8cmFuZG9tfHx8fHx8fHx8MTcxNzc3NTg2M3w&ixlib=rb-4.0.3&q=80&w=1080',
    },
    image11Alt: {
      type: String,
      default: 'Hero Image',
    },
    image3Src: {
      type: String,
      default:
        'https://images.unsplash.com/photo-1467806757054-808649965a76?crop=entropy&cs=tinysrgb&fit=max&fm=jpg&ixid=M3w5MTMyMXwwfDF8cmFuZG9tfHx8fHx8fHx8MTcxNzc3NTg2Mnw&ixlib=rb-4.0.3&q=80&w=1080',
    },
    image10Alt: {
      type: String,
      default: 'Hero Image',
    },
    image1Alt: {
      type: String,
      default: 'Modern Dating Webapp',
    },
    image4Alt: {
      type: String,
      default: 'Hero Image',
    },
    image8Alt: {
      type: String,
      default: 'Hero Image',
    },
    image3Alt: {
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
.hero17-header78 {
  gap: var(--dl-space-space-threeunits);
  width: 100%;
  height: auto;
  display: flex;
  overflow: hidden;
  position: relative;
  align-items: center;
  flex-shrink: 0;
  flex-direction: column;
}
.hero17-column {
  gap: var(--dl-space-space-oneandhalfunits);
  width: auto;
  display: flex;
  align-items: center;
  flex-direction: column;
  padding-bottom: var(--dl-space-space-unit);
}
.hero17-content {
  gap: var(--dl-space-space-oneandhalfunits);
  display: flex;
  align-self: stretch;
  align-items: center;
  flex-direction: column;
}
.hero17-text {
  text-align: center;
}
.hero17-text1 {
  text-align: center;
}
.hero17-actions {
  gap: var(--dl-space-space-unit);
  display: flex;
  align-items: flex-start;
  padding-top: var(--dl-space-space-unit);
}
.hero17-content1 {
  gap: var(--dl-space-space-oneandhalfunits);
  width: 100%;
  display: flex;
  position: relative;
  align-items: flex-start;
  flex-direction: column;
}
.hero17-row-container {
  width: 100%;
}
.hero17-placeholder-image {
  width: 400px;
  height: 400px;
}
.hero17-placeholder-image01 {
  width: 400px;
  height: 400px;
}
.hero17-placeholder-image02 {
  width: 400px;
  height: 400px;
}
.hero17-placeholder-image03 {
  width: 400px;
  height: 400px;
}
.hero17-placeholder-image04 {
  width: 400px;
  height: 400px;
}
.hero17-placeholder-image05 {
  width: 400px;
  height: 400px;
}
.hero17-placeholder-image06 {
  width: 400px;
  height: 400px;
}
.hero17-placeholder-image07 {
  width: 400px;
  height: 400px;
}
.hero17-placeholder-image08 {
  width: 400px;
  height: 400px;
}
.hero17-placeholder-image09 {
  width: 400px;
  height: 400px;
}
.hero17-placeholder-image10 {
  width: 400px;
  height: 400px;
}
.hero17-placeholder-image11 {
  width: 400px;
  height: 400px;
}
.hero17-row-container1 {
  width: 100%;
}
.hero17-placeholder-image12 {
  width: 400px;
  height: 400px;
}
.hero17-placeholder-image13 {
  width: 400px;
  height: 400px;
}
.hero17-placeholder-image14 {
  width: 400px;
  height: 400px;
}
.hero17-placeholder-image15 {
  width: 400px;
  height: 400px;
}
.hero17-placeholder-image16 {
  width: 400px;
  height: 400px;
}
.hero17-placeholder-image17 {
  width: 400px;
  height: 400px;
}
.hero17-placeholder-image18 {
  width: 400px;
  height: 400px;
}
.hero17-placeholder-image19 {
  width: 400px;
  height: 400px;
}
.hero17-placeholder-image20 {
  width: 400px;
  height: 400px;
}
.hero17-placeholder-image21 {
  width: 400px;
  height: 400px;
}
.hero17-placeholder-image22 {
  width: 400px;
  height: 400px;
}
.hero17-placeholder-image23 {
  width: 400px;
  height: 400px;
}
.hero17-container1 {
  display: contents;
}
@media(max-width: 767px) {
  .hero17-content1 {
    width: 100%;
  }
}
@media(max-width: 479px) {
  .hero17-actions {
    width: 100%;
    flex-direction: column;
  }
  .hero17-button {
    width: 100%;
  }
  .hero17-button1 {
    width: 100%;
  }
}
</style>
