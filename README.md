# আর-রাহমান AI (Ar Rahman AI)

A Bengali-first responsive starter interface for madrasa dars transcription, YouTube transcript retrieval, Arabic-to-Bengali translation, text-to-speech, and document export.

## Current status

This commit adds the front-end scaffold only. Transcription, YouTube retrieval, translation, text-to-speech, and DOCX/PDF export are intentionally not reported as working because secure backend integrations have not yet been configured.

## Deploy on Netlify

1. In Netlify, choose Add new project, then Import an existing project.
2. Connect GitHub and select muslimkontoshor-tech/ai-voice-to-text.
3. Set the publish directory to . ; no build command is required for this starter.
4. Deploy a preview first and test the UI.

## Required next engineering steps

- Add secure Netlify Functions for translation and speech services.
- Configure secrets in Netlify environment variables (never commit API keys).
- Implement resumable chunk processing for long audio/video and honest progress/error states.
- Implement YouTube captions retrieval only through supported, permitted methods.
- Add tested DOCX/PDF generation and right-to-left Arabic formatting.
- Test all integrations before claiming production readiness.
