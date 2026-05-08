# Quranic Arabic Tutor for AI Agents 🕌

An interactive, voice-first AI tutor skill designed for the agentic frameworks like Hermes or OpenClaw. This skill transforms your agent into an expert, patient Arabic tutor that guides users from zero knowledge (the alphabet) to reading full Quranic verses with basic Tajweed.

## ✨ Features

* **Voice-Driven Training:** Fully utilizes voice messages for a back-and-forth learning experience. The agent demonstrates proper pronunciation (Tajweed and Makharij) and evaluates your voice replies.
* **Structured Curriculum:** A strict, step-by-step progression through 5 phases:
    1. Foundations (Alphabet & Articulation)
    2. Vowels (Harakat)
    3. Connectors & Stops
    4. Basic Tajweed Rules
    5. Quranic Application
* **Interactive Gatekeeping:** End-of-phase quizzes ensure 100% mastery before allowing progression to the next phase.
* **Phonetic Focus:** Clear English transliterations paired with precise explanations of how sounds are formed in the mouth.

## ⚙️ Prerequisites

* **Premium TTS Provider (Crucial):** Default text-to-speech providers (like Edge TTS) may struggle with accurate Arabic Makharij. For a proper learning experience, I recommended that you configure your agent with a provider capable of handling high-fidelity multilingual Arabic text:
    * [ElevenLabs](https://elevenlabs.io) *(Ensure you select a **multilingual voice** that supports both Arabic and English)*
    * [OpenAI TTS](https://platform.openai.com/docs/guides/text-to-speech)
    * [Narakeet](https://www.narakeet.com)
* **Separate Topic/Channel:** I highly recommend starting off this skill in a separate topic or channel in your agent messaging platform such as Telegram/Discord/Slack etc. This way it is easier and cleaner to track your progress and continue lessons from where you left off.

## 🚀 Installation

1.  Download the `arabic tutor.md` skill file from this repository.
2.  Ask your agent to install the skill.
3.  If you setup Text to Speech (TTS), restart your agent's gateway/service to load the new skill.

## 💬 Usage

Once the skill is active, simply message your agent to kick off a session:

> **User:** "Start the Quran Arabic tutor skill."
>
> **Agent:** "Welcome! Before we begin, please note that accurate text-to-speech is critical..."

The agent will automatically track your progress. When returning for a new session, it will prompt you to review your last lesson or proceed to the next step.
