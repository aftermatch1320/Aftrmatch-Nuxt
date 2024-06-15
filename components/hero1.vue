<template>
  <div class="thq-section-padding">
    <h1 class="thq-heading-1 hero1-heading1">{{ heading1 }}</h1>
    <div class="hero1-max-width thq-section-max-width">
      <div class="thq-flex-row hero1-container">
        <div class="hero1-column">
          <div class="hero1-content">
            <h1 class="thq-heading-1 hero1-heading11">{{ heading1 }}</h1>
            <p class="thq-body-large hero1-content1">{{ content1 }}</p>
          </div>
          <div class="hero1-actions">
            <button class="thq-button-filled hero1-button">
              <span class="thq-body-small">{{ action1 }}</span>
            </button>
            <button class="thq-button-outline hero1-button1">
              <span class="thq-body-small">{{ action2 }}</span>
            </button>
          </div>
        </div>
        <div class="hero1-container1">
          <img
            :alt="image1Alt"
            :src="image1Src"
            class="hero1-image1 thq-img-ratio-4-3"
          />
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'Hero1',
  props: {
    heading1: {
      type: String,
      default: 'Find Your Perfect Match',
    },
    action2: {
      type: String,
      default: 'Sign Up Now',
    },
    image1Alt: {
      type: String,
      default: 'Modern Dating Webapp',
    },
    content1: {
      type: String,
      default:
        'Join our modern dating webapp and discover meaningful connections with like-minded individuals.',
    },
    action1: {
      type: String,
      default: 'Learn More',
    },
    image1Src: {
      type: String,
      default:
        'https://images.unsplash.com/photo-1517816981644-e0e3de7743e5?crop=entropy&cs=tinysrgb&fit=max&fm=jpg&ixid=M3w5MTMyMXwwfDF8cmFuZG9tfHx8fHx8fHx8MTcxNzc3NTYxNHw&ixlib=rb-4.0.3&q=80&w=1080',
    },
  },
}
</script>

<style scoped>
.hero1-max-width {
  display: flex;
  align-items: center;
  flex-direction: column;
  justify-content: center;
}
.hero1-column {
  gap: 24px;
  flex: 1;
  display: flex;
  align-items: flex-start;
  flex-direction: column;
}
.hero1-content {
  gap: 24px;
  display: flex;
  align-self: stretch;
  align-items: flex-start;
  flex-direction: column;
}
.hero1-actions {
  gap: var(--dl-space-space-unit);
  display: flex;
  align-items: flex-start;
}
.hero1-container1 {
  flex: 1;
  display: flex;
  position: relative;
  align-items: center;
  padding-top: 35%;
  justify-content: flex-start;
}
.hero1-image1 {
  left: 0px;
  width: 100%;
  bottom: 0px;
  height: 100%;
  position: absolute;
  flex-grow: 1;
  object-fit: cover;
}
@media(max-width: 991px) {
  .hero1-container {
    flex-direction: column;
  }
  .hero1-container1 {
    width: 100%;
    padding-top: 56.25%;
  }
}
@media(max-width: 767px) {
  .hero1-heading1 {
    text-align: center;
  }
  .hero1-heading11 {
    text-align: center;
  }
  .hero1-content1 {
    text-align: center;
  }
  .hero1-actions {
    width: 100%;
    justify-content: center;
  }
  .hero1-image1 {
    width: 100%;
  }
}
@media(max-width: 479px) {
  .hero1-actions {
    flex-direction: column;
  }
  .hero1-button {
    width: 100%;
  }
  .hero1-button1 {
    width: 100%;
  }
}
</style>
