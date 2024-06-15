<template>
  <div class="features4-layout301 thq-section-padding">
    <div class="features4-max-width thq-section-max-width">
      <h2 class="features4-text thq-heading-2">{{ sectionTitle }}</h2>
      <div class="features4-row thq-grid-auto-300">
        <div class="features4-feature1">
          <img
            :alt="feature1ImageAlt"
            :src="feature1ImageSrc"
            class="thq-img-ratio-4-3"
          />
          <div class="features4-content thq-flex-column">
            <div class="features4-section-title thq-flex-column">
              <h3 class="features4-title1 thq-heading-3">{{ feature1Title }}</h3>
              <span class="features4-description1 thq-body-small">
                {{ feature1Description }}
              </span>
            </div>
            <div class="features4-action thq-flex-row">
              <button class="thq-button-flat features4-button">
                <span class="thq-body-small">{{ feature1Button }}</span>
                <svg viewBox="0 0 1024 1024" class="thq-icon-small">
                  <path
                    d="M426 256l256 256-256 256-60-60 196-196-196-196z"
                  ></path>
                </svg>
              </button>
            </div>
          </div>
        </div>
        <div class="features4-feature2">
          <img
            :alt="feature2ImageAlt"
            :src="feature2ImageSrc"
            class="thq-img-ratio-4-3"
          />
          <div class="features4-content1 thq-flex-column">
            <div class="features4-section-title1 thq-flex-column">
              <strong class="features4-title2 thq-heading-3">
                {{ feature2Title }}
              </strong>
              <span class="features4-description2 thq-body-small">
                {{ feature2Description }}
              </span>
            </div>
            <div class="features4-action1 thq-flex-row">
              <button class="thq-button-flat features4-button1">
                <span class="thq-body-small features4-action2">
                  {{ feature2Button }}
                </span>
                <svg viewBox="0 0 1024 1024" class="thq-icon-small">
                  <path
                    d="M426 256l256 256-256 256-60-60 196-196-196-196z"
                  ></path>
                </svg>
              </button>
            </div>
          </div>
        </div>
        <div class="features4-feature3">
          <img
            :alt="feature3ImageAlt"
            :src="feature3ImageSrc"
            class="thq-img-ratio-4-3"
          />
          <div class="features4-content2 thq-flex-column">
            <div class="features4-section-title2 thq-flex-column">
              <strong class="features4-title3 thq-heading-3">
                {{ feature3Title }}
              </strong>
              <span class="features4-description3 thq-body-small">
                {{ feature3Description }}
              </span>
            </div>
            <div class="features4-action2 thq-flex-row">
              <button class="thq-button-flat features4-button2">
                <span class="thq-body-small">{{ feature3Button }}</span>
                <svg viewBox="0 0 1024 1024" class="thq-icon-small">
                  <path
                    d="M426 256l256 256-256 256-60-60 196-196-196-196z"
                  ></path>
                </svg>
              </button>
            </div>
          </div>
        </div>
        <div class="features4-feature4">
          <img
            :alt="feature4ImageAlt"
            :src="feature4ImageSrc"
            class="thq-img-ratio-4-3"
          />
          <div class="features4-content3 thq-flex-column">
            <div class="features4-section-title3 thq-flex-column">
              <strong class="features4-title4 thq-heading-3">
                {{ feature4Title }}
              </strong>
              <span class="features4-description4 thq-body-small">
                {{ feature4Description }}
              </span>
            </div>
            <div class="features4-action3 thq-flex-row">
              <button class="thq-button-flat features4-button3">
                <span class="thq-body-small">{{ feature4Button }}</span>
                <svg viewBox="0 0 1024 1024" class="thq-icon-small">
                  <path
                    d="M426 256l256 256-256 256-60-60 196-196-196-196z"
                  ></path>
                </svg>
              </button>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'Features4',
  props: {
    feature4Button: {
      type: String,
      default: 'Discover More',
    },
    feature2Button: {
      type: String,
      default: 'Start Chatting',
    },
    feature1Description: {
      type: String,
      default:
        'Bring your match from any platform and explore our chat and games features on the app with them.',
    },
    feature3Button: {
      type: String,
      default: 'Verify Profile',
    },
    feature3ImageSrc: {
      type: String,
      default: 'https://play.teleporthq.io/static/svg/default-img.svg',
    },
    sectionTitle: {
      type: String,
      default: "What Set's Us Apart In Dating World",
    },
    feature1ImageAlt: {
      type: String,
      default: "What Set's Us Apart",
    },
    feature2Title: {
      type: String,
      default: 'SOS Emergency and Chat Support',
    },
    feature1Title: {
      type: String,
      default: 'Onboard other app users directly to AfterMatch',
    },
    feature4Description: {
      type: String,
      default:
        'Allows you to be seen only by those who meet your dating criteria',
    },
    feature2ImageAlt: {
      type: String,
      default: 'Interactive Messaging',
    },
    feature4ImageSrc: {
      type: String,
      default:
        'https://images.unsplash.com/photo-1516799868487-7b6cc0504a3e?crop=entropy&cs=tinysrgb&fit=max&fm=jpg&ixid=M3w5MTMyMXwwfDF8cmFuZG9tfHx8fHx8fHx8MTcxNzg2MjgxOXw&ixlib=rb-4.0.3&q=80&w=1080',
    },
    feature2ImageSrc: {
      type: String,
      default:
        'https://images.unsplash.com/photo-1518717283029-d622d998185a?crop=entropy&cs=tinysrgb&fit=max&fm=jpg&ixid=M3w5MTMyMXwwfDF8cmFuZG9tfHx8fHx8fHx8MTcxNzg2MjgxOXw&ixlib=rb-4.0.3&q=80&w=1080',
    },
    feature3Description: {
      type: String,
      default:
        'Play Games, Invite your connections and unlock the new way of building meaningful conversations',
    },
    feature3ImageAlt: {
      type: String,
      default: 'Profile Verification',
    },
    feature4Title: {
      type: String,
      default: 'Restricted Purpose based Swipes as per criteria',
    },
    feature1Button: {
      type: String,
      default: 'Learn More',
    },
    feature4ImageAlt: {
      type: String,
      default: 'Modern Matching Features',
    },
    feature2Description: {
      type: String,
      default:
        'SOS emergency and c hat support available for suspicious situations',
    },
    feature1ImageSrc: {
      type: String,
      default:
        'https://images.unsplash.com/photo-1644661847825-56b30afd7f92?crop=entropy&cs=tinysrgb&fit=max&fm=jpg&ixid=M3w5MTMyMXwwfDF8cmFuZG9tfHx8fHx8fHx8MTcxNzg2MjgxOXw&ixlib=rb-4.0.3&q=80&w=1080',
    },
    feature3Title: {
      type: String,
      default: 'Enjoy Mini Games with Partners',
    },
  },
}
</script>

<style scoped>
.features4-layout301 {
  gap: var(--dl-space-space-fiveunits);
  width: 100%;
  height: auto;
  display: flex;
  overflow: hidden;
  position: relative;
  align-items: center;
  flex-shrink: 0;
  flex-direction: column;
  justify-content: center;
}
.features4-max-width {
  gap: var(--dl-space-space-threeunits);
  display: flex;
  align-items: center;
  flex-direction: column;
}
.features4-text {
  text-align: center;
}
.features4-row {
  width: 100%;
}
.features4-feature1 {
  gap: var(--dl-space-space-twounits);
  flex: 1;
  width: auto;
  display: flex;
  overflow: hidden;
  max-width: 600px;
  align-items: flex-start;
  flex-shrink: 0;
  flex-direction: column;
}
.features4-content {
  align-self: stretch;
  align-items: center;
}
.features4-section-title {
  align-self: stretch;
  align-items: center;
}
.features4-title1 {
  text-align: center;
}
.features4-description1 {
  text-align: center;
}
.features4-action {
  align-self: stretch;
  align-items: stretch;
  justify-content: center;
}
.features4-feature2 {
  gap: var(--dl-space-space-twounits);
  flex: 1;
  width: auto;
  display: flex;
  overflow: hidden;
  max-width: 600px;
  align-items: flex-start;
  flex-shrink: 0;
  flex-direction: column;
}
.features4-content1 {
  align-self: stretch;
  align-items: center;
}
.features4-section-title1 {
  align-self: stretch;
  align-items: center;
}
.features4-title2 {
  text-align: center;
}
.features4-description2 {
  text-align: center;
}
.features4-action1 {
  align-self: stretch;
  align-items: stretch;
  justify-content: center;
}
.features4-feature3 {
  gap: var(--dl-space-space-twounits);
  flex: 1;
  width: auto;
  display: flex;
  overflow: hidden;
  max-width: 600px;
  align-items: flex-start;
  flex-shrink: 0;
  flex-direction: column;
}
.features4-content2 {
  align-self: stretch;
  align-items: center;
}
.features4-section-title2 {
  align-self: stretch;
  align-items: center;
}
.features4-title3 {
  text-align: center;
}
.features4-description3 {
  text-align: center;
}
.features4-action2 {
  align-self: stretch;
  align-items: stretch;
  justify-content: center;
}
.features4-feature4 {
  gap: var(--dl-space-space-twounits);
  flex: 1;
  width: auto;
  display: flex;
  overflow: hidden;
  max-width: 600px;
  align-items: flex-start;
  flex-shrink: 0;
  flex-direction: column;
}
.features4-content3 {
  align-self: stretch;
  align-items: center;
}
.features4-section-title3 {
  align-self: stretch;
  align-items: center;
}
.features4-title4 {
  text-align: center;
}
.features4-description4 {
  text-align: center;
}
.features4-action3 {
  align-self: stretch;
  align-items: stretch;
  justify-content: center;
}
@media(max-width: 1600px) {
  .features4-button {
    opacity: 0;
  }
  .features4-button1 {
    opacity: 0;
  }
  .features4-action2 {
    opacity: 0;
  }
  .features4-button2 {
    opacity: 0;
  }
  .features4-button3 {
    opacity: 0;
  }
}
@media(max-width: 991px) {
  .features4-row {
    width: auto;
    align-items: center;
    flex-direction: column;
  }
  .features4-feature1 {
    width: 100%;
  }
  .features4-feature2 {
    width: 100%;
  }
  .features4-feature3 {
    width: 100%;
  }
  .features4-feature4 {
    width: 100%;
  }
}
@media(max-width: 767px) {
  .features4-text {
    text-align: center;
  }
}
@media(max-width: 479px) {
  .features4-max-width {
    gap: var(--dl-space-space-oneandhalfunits);
  }
}
</style>
