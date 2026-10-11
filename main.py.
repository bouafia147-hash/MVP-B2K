
from kivy.app import App
from kivy.core.window import Window
from kivy.uix.boxlayout import BoxLayout
from kivy.uix.label import Label
from kivy.uix.button import Button
from kivy.metrics import dp
import webbrowser

CHANNEL = "https://www.youtube.com/@siradj-j4w"


class MVPB2K(App):
    def build(self):
        Window.clearcolor = (0.035, 0.035, 0.035, 1)

        root = BoxLayout(
            orientation="vertical",
            padding=dp(24),
            spacing=dp(20)
        )

        root.add_widget(Label(
            text="[b]MVP B2K![/b]",
            markup=True,
            font_size=dp(38),
            color=(1, 0.04, 0.08, 1)
        ))

        root.add_widget(Label(
            text="OFFICIAL GAMING CHANNEL",
            font_size=dp(16),
            color=(1, 1, 1, 1)
        ))

        btn = Button(
            text="▶  OPEN MY YOUTUBE",
            font_size=dp(18),
            background_normal="",
            background_color=(0.9, 0.02, 0.06, 1),
            size_hint_y=None,
            height=dp(60)
        )
        btn.bind(on_release=lambda *_: webbrowser.open(CHANNEL))
        root.add_widget(btn)

        root.add_widget(Label(
            text="SUBSCRIBE FOR MORE GAMING!",
            color=(1, 0.1, 0.15, 1)
        ))

        return root


MVPB2K().run()

