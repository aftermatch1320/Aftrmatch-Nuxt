<template>
  <div class="thq-section-padding">
    <div class="hero11-max-width thq-section-max-width">
      <div class="thq-flex-row hero11-container">
        <div class="hero11-column">
          <div class="hero11-content">
            <h1 class="thq-heading-1 hero11-heading1">{{ heading1 }}</h1>
            <p class="thq-body-large hero11-content1">{{ content1 }}</p>
          </div>
          <div class="hero11-actions">
            <button class="thq-button-filled hero11-button">
              <span class="thq-body-small">{{ action1 }}</span>
            </button>
            <button class="thq-button-outline hero11-button1">
              <span class="thq-body-small">{{ action2 }}</span>
            </button>
          </div>
        </div>
        <div class="hero11-container1">
          <img
            :alt="image1Alt"
            :src="image1Src"
            class="hero11-image1 thq-img-ratio-4-3"
          />
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'Hero11',
  props: {
    image1Src: {
      type: String,
      default:
        'https://images.unsplash.com/photo-1517816981644-e0e3de7743e5?crop=entropy&cs=tinysrgb&fit=max&fm=jpg&ixid=M3w5MTMyMXwwfDF8cmFuZG9tfHx8fHx8fHx8MTcxNzc3NTYxNHw&ixlib=rb-4.0.3&q=80&w=1080',
    },
    content1: {
      type: String,
      default:
        'Join our modern dating webapp and discover meaningful connections with like-minded individuals.',
    },
    action2: {
      type: String,
      default: 'Sign Up Now',
    },
    image1Alt: {
      type: String,
      default: 'Modern Dating Webapp',
    },
    heading1: {
      type: String,
      default: 'Find Your Perfect Match',
    },
    action1: {
      type: String,
      default: 'Learn More',
    },
  },
}
</script>

<style scoped>
.hero11-max-width {
  display: flex;
  align-items: center;
  flex-direction: column;
  justify-content: center;
}
.hero11-column {
  gap: 24px;
  flex: 1;
  display: flex;
  align-items: flex-start;
  flex-direction: column;
}
.hero11-content {
  gap: 24px;
  display: flex;
  align-self: stretch;
  align-items: flex-start;
  flex-direction: column;
}
.hero11-actions {
  gap: var(--dl-space-space-unit);
  display: flex;
  align-items: flex-start;
}
.hero11-container1 {
  flex: 1;
  display: flex;
  position: relative;
  align-items: center;
  padding-top: 35%;
  justify-content: flex-start;
}
.hero11-image1 {
  left: 0px;
  width: 100%;
  bottom: 0px;
  height: 100%;
  position: absolute;
  flex-grow: 1;
  object-fit: cover;
}
@media(max-width: 991px) {
  .hero11-container {
    flex-direction: column;
  }
  .hero11-container1 {
    width: 100%;
    padding-top: 56.25%;
  }
}
@media(max-width: 767px) {
  .hero11-heading1 {
    text-align: center;
  }
  .hero11-content1 {
    text-align: center;
  }
  .hero11-actions {
    width: 100%;
    justify-content: center;
  }
  .hero11-image1 {
    width: 100%;
  }
}
@media(max-width: 479px) {
  .hero11-actions {
    flex-direction: column;
  }
  .hero11-button {
    width: 100%;
  }
  .hero11-button1 {
    width: 100%;
  }
}
</style>
