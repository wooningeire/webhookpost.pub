# webhookpost
Single-page app that allows users to manually post messages through a WebHook.

This `README` was not originally included in this project.

`index.html` has been edited to remove private WebHook URLs.

## Query variables
As a personal app, several field presets are made available for certain purposes. These presets are available through the URL query variable `preset` and can be accessed by setting it to any of the values below (ie, adding `?preset=6` or similar to the end of the URL).
| Value | Description														  |
|---	|---																  |
| `1` 	| `@everyone` followed by a YouTube URL; used for manual YouTube feed |
| `2`\*	| Alternate general WebHook link									  |
| `3`	| Blank avatar and invisible message text							  |
| `4`\* | Sandbox WebHook link												  |
| `5`\* | Spam WebHook link													  |
| `6`	| Demon of PaRappa the Rapper										  |
</table>
\* identical to empty preset due to removed WebHook link
