<template>
  <div class="features10-layout300 thq-section-padding">
    <div class="features10-max-width thq-flex-column thq-section-max-width">
      <div class="features10-section-title thq-flex-column">
        <span class="thq-body-small features10-text">{{ slogan }}</span>
        <h2 class="thq-heading-2 features10-text1">{{ sectionTitle }}</h2>
        <p class="features10-text2 thq-body-large">{{ sectionDescription }}</p>
      </div>
      <div class="features10-content thq-grid-auto-300">
        <div class="features10-feature1 thq-flex-column">
          <img
            :alt="feature1ImageAlt"
            :src="feature1ImageSrc"
            class="thq-img-ratio-4-3 features10-feature1-image"
          />
          <h3 class="features10-feature1-title thq-heading-3">
            {{ feature1Title }}
          </h3>
          <span class="thq-body-small">{{ feature1Description }}</span>
        </div>
        <div class="features10-feature2 thq-flex-column">
          <img
            :alt="feature2ImageAlt"
            :src="feature2ImageSrc"
            class="thq-img-ratio-4-3 features10-feature2-image"
          />
          <h3 class="thq-heading-3">{{ feature2Title }}</h3>
          <span class="thq-body-small">{{ feature2Description }}</span>
        </div>
        <div class="features10-feature3 thq-flex-column">
          <img
            :alt="feature3ImageAlt"
            :src="feature3ImageSrc"
            class="thq-img-ratio-4-3"
          />
          <h3 class="thq-heading-3">{{ feature3Title }}</h3>
          <span class="thq-body-small">{{ feature3Description }}</span>
        </div>
      </div>
      <div class="features10-actions thq-flex-row">
        <button class="features10-button thq-button-filled">
          <span class="thq-body-small">{{ mainAction }}</span>
        </button>
        <button class="features10-button1 thq-button-outline">
          <span class="thq-body-small">{{ secondaryAction }}</span>
        </button>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'Features10',
  props: {
    feature3Title: {
      type: String,
      default: 'Profile Verification',
    },
    sectionTitle: {
      type: String,
      default: 'Features',
    },
    feature1Title: {
      type: String,
      default: 'Advanced Matching Algorithm',
    },
    feature1ImageSrc: {
      type: String,
      default:
        'https://images.unsplash.com/photo-1601421160577-953240c6e37b?crop=entropy&cs=tinysrgb&fit=max&fm=jpg&ixid=M3w5MTMyMXwwfDF8cmFuZG9tfHx8fHx8fHx8MTcxNzc3NTYxNXw&ixlib=rb-4.0.3&q=80&w=1080',
    },
    secondaryAction: {
      type: String,
      default: 'Chat instantly with your matches',
    },
    feature2ImageSrc: {
      type: String,
      default:
        'https://images.unsplash.com/photo-1572985025310-cc8cafbbf394?crop=entropy&cs=tinysrgb&fit=max&fm=jpg&ixid=M3w5MTMyMXwwfDF8cmFuZG9tfHx8fHx8fHx8MTcxNzc3NTYxNXw&ixlib=rb-4.0.3&q=80&w=1080',
    },
    feature2Description: {
      type: String,
      default:
        'Engage in meaningful conversations with your matches through our user-friendly messaging interface.',
    },
    feature3ImageAlt: {
      type: String,
      default: 'Profile Verification Image',
    },
    feature3Description: {
      type: String,
      default:
        'Ensure authenticity and trust by verifying your profile to attract genuine connections.',
    },
    heading: {
      type: String,
      default: 'Modern Features',
    },
    feature1Description: {
      type: String,
      default:
        'Our app uses cutting-edge technology to match you with compatible partners based on your preferences.',
    },
    feature3ImageSrc: {
      type: String,
      default:
        'https://images.unsplash.com/photo-1530027618771-db9eb5d2f905?crop=entropy&cs=tinysrgb&fit=max&fm=jpg&ixid=M3w5MTMyMXwwfDF8cmFuZG9tfHx8fHx8fHx8MTcxNzc3NTYxNXw&ixlib=rb-4.0.3&q=80&w=1080',
    },
    feature1ImageAlt: {
      type: String,
      default: 'Advanced Matching Algorithm Image',
    },
    mainAction: {
      type: String,
      default: 'Match with like-minded individuals',
    },
    feature2Title: {
      type: String,
      default: 'Interactive Messaging',
    },
    feature2ImageAlt: {
      type: String,
      default: 'Interactive Messaging Image',
    },
    sectionDescription: {
      type: String,
      default: 'Explore the modern features of our dating webapp',
    },
    slogan: {
      type: String,
      default: 'Find your perfect match with ease',
    },
  },
}
</script>

<style scoped>
.features10-layout300 {
  width: 100%;
  height: auto;
  display: flex;
  overflow: hidden;
  position: relative;
  align-items: center;
  flex-shrink: 0;
  flex-direction: column;
}
.features10-max-width {
  gap: var(--dl-space-space-threeunits);
  align-items: center;
}
.features10-section-title {
  align-items: center;
}
.features10-text2 {
  text-align: center;
}
.features10-content {
  align-self: stretch;
  align-items: center;
}
.features10-feature1 {
  align-items: flex-start;
}
.features10-feature1-title {
  text-align: center;
}
.features10-feature2 {
  align-items: flex-start;
}
.features10-feature3 {
  align-items: flex-start;
}
.features10-actions {
  align-items: flex-start;
}
.features10-button {
  padding-top: var(--dl-space-space-halfunit);
  padding-left: var(--dl-space-space-oneandhalfunits);
  padding-right: var(--dl-space-space-oneandhalfunits);
  padding-bottom: var(--dl-space-space-halfunit);
}
.features10-button1 {
  padding-top: var(--dl-space-space-halfunit);
  padding-left: var(--dl-space-space-oneandhalfunits);
  padding-right: var(--dl-space-space-oneandhalfunits);
  padding-bottom: var(--dl-space-space-halfunit);
}
@media(max-width: 1600px) {
  .features10-section-title {
    opacity: 0;
  }
  .features10-text {
    opacity: 0;
  }
  .features10-feature1-image {
    border-color: var(--dl-color-theme-neutral-dark);
    border-width: 1px;
  }
  .features10-feature2 {
    position: relative;
  }
  .features10-feature2-image {
    z-index: 100;
    box-shadow: 5px 5px 10px 0px #d4d4d4;
  }
}
@media(max-width: 991px) {
  .features10-section-title {
    width: 100%;
  }
}
@media(max-width: 767px) {
  .features10-section-title {
    width: auto;
  }
  .features10-text1 {
    text-align: center;
  }
  .features10-feature2 {
    width: auto;
  }
  .features10-feature3 {
    width: auto;
  }
}
@media(max-width: 479px) {
  .features10-max-width {
    gap: var(--dl-space-space-oneandhalfunits);
  }
  .features10-actions {
    width: 100%;
    flex-direction: column;
  }
  .features10-button {
    width: 100%;
  }
  .features10-button1 {
    width: 100%;
  }
}
</style>
