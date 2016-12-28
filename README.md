# ElegantArcLayout
ArcLayout is a ViewGroup extends FrameLayout.
The FrameLayout has an acr at the top edge or bottom edge.
I learned ArcLayout from Git project who owns it https://github.com/florent37/ArcLayout.

#Issues.
1.Version Support.It uses OutlineProvider to accomplish outline clipping, but OutlineProvider has version limmit(min SDK > 14).
2.Background. When we apply ArcLayout as a parent layout and use backgound attr, it fails.
