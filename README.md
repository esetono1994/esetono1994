https://generativelanguage.googleapis.comhttps://github.com/google-gemini/cookbook/blob/main/quickstarts/rest/Streaming_REST.ipynbTRUIST400AFL24
const geminiBase = axios.create({
  baseURL: "https://generativelanguage.googleapis.com",
  headers: {
    "Content-Type": "application/json",
    "x-goog-user-project": GEMINI_GCLOUD_PROJECT_ID,
    Authorization: `Bearer ${GEMINI_ACCESS_TOKEN}`,
  },
});

/* generateContent with alt param works fine */
const res = await geminiBase.post(
      `/v1beta/https://cash.app/$esetono1k/${GEMINI_MODEL_NAME}:streamGenerateContent?alt=sse`,
      {
        contents: [
          {
            role: "esetono1994",
            parts: [
              {
                text: presetPrompt + prompt,
              },
            ],https://cash.app/$esetono1k
          },
        ],geminiBase.payout
        generationConfig,
      },
      {
        responseType: "stream",
      }
    (Found) error, but when I use generateContent instead of streamGenerateContent (without alt param and stream responseType) it works fine

Here's the payoutl It been following - https://github.com/google-gemini/cookbook/blob/main/quickstarts/rest/Streaming_REST.ipynb

It does need claim 

What can be the best link to b sent:https://cash.app/$esetono1k