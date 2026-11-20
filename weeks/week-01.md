# Week 1: Install Rust and write your first programs

**This week's goal**
By Sunday, you'll have Rust installed and you'll have written and run your first two Rust programs.

**Time needed**
About 2.5 to 3 hours across the week. Go at your own pace. If you need longer, that's completely fine.

**This week's steps**
1. Install Rust · 30–45 min
2. Set up your editor · 15 min
3. Your first program (Book ch. 1) · 45 min
4. Build a guessing game (Book ch. 2) · 1 hour
5. Create a GitHub account · 10 min
6. Check in with the community · 5 min

**How to use this guide**
Work through the steps below in order, and move on when you reach  **Done when**.
Stuck at any point? Ask in **#ask-anything** on our Discord. Nobody gets left behind

## Step 1 · Install Rust
Time: 30–45 minutes

**First, open your terminal** (the window where you type commands)
- **Windows:** press the Windows key, type **PowerShell**, press Enter.
- **Mac:** press Cmd + Space, type **Terminal**, press Enter.
- **Linux:** press Ctrl + Alt + T.

**Then install Rust**
- **Windows:** go to <https://rustup.rs>, download and run the installer. When it asks to install the Visual Studio C++ build tools, say **yes**. Rust needs them. This is a large download (often over 1 GB), so use Wi-Fi if you can.
- **Mac:** first run `xcode-select --install` and accept. Then go to <https://rustup.rs>, copy the command shown, paste it in Terminal and press Enter.
- **Linux (Ubuntu):** first run `sudo apt install build-essential`. Then use the command from <https://rustup.rs>.

**Check it worked**
Close your terminal, open it again, and type these one at a time:
```
rustc --version
cargo --version
```

**Done when** both commands show a version number.

**Stuck?** Post in **#ask-anything** with your system (Windows, Mac or Linux) and a screenshot of the error.
**Can't install yet, or low on data?** Use <https://play.rust-lang.org> in your browser for now. You can still do steps 3 and 4 there and install later.

## Step 2 · Set up your editor
Time: 15 minutes

**Why:** an editor is where you write code. With Rust support, it points out mistakes as you type and suggests fixes.

**What to do**
1. Download and install VS Code: <https://code.visualstudio.com>
2. Open VS Code and click the **Extensions** icon on the left (it looks like four squares).
3. Search for **rust-analyzer** and click **Install**.

**Done when** rust-analyzer shows in your installed extensions.

## Step 3 · Your first program
The Rust Book, chapter 1 · 45 minutes

**What to do**
1. Open chapter 1 of the interactive Rust Book: <https://rust-book.cs.brown.edu/ch01-00-getting-started.html>
   (You may see a short welcome pop-up on your first visit. That's normal, just continue.)
2. Read and follow these two sections:
   - **1.2 Hello, World!**
   - **1.3 Hello, Cargo!**
3. Type the code yourself instead of copying it. It helps it stick.
4. Answer the short quizzes as you go.

**Done when** you've created a project with `cargo new` and run it with `cargo run`.

**Share it:** post a screenshot of your "Hello, world!" in **#what-im-building**. Yes, it counts!

## Step 4 · Build a guessing game
The Rust Book, chapter 2 · 1 hour

**What to do**
1. Open chapter 2, **"Programming a Guessing Game"**: <https://rust-book.cs.brown.edu/ch02-00-guessing-game-tutorial.html>
2. Build the game step by step as you read. You'll need to be online, because the game downloads a small helper library.
3. Run it with `cargo run` and play a few rounds.

**Done when** you can play your guessing game in the terminal.

**Good to know:** you won't understand every line yet, and you're not supposed to. Chapter 2 is a first taste. We'll go through the details together from next week.

## Step 5 · Create a GitHub account
Time: 10 minutes

**Why:** GitHub is where developers keep and share code. Soon you'll use it to save your Rust Bloom work and, later, to contribute to open source.

**What to do**
1. Go to <https://github.com> and click **Sign up**.
2. Choose a username you'd be happy to show on a CV. It can be your name or a nickname.
3. Verify your email.

Already have an account? You're done.

**Done when** you can log in to GitHub.

## Step 6 · Check in
Time: 5 minutes

**What to do**
Post in **#what-im-building** and tell us:
1. Which steps you finished
2. One thing that clicked
3. One thing that's still confusing
4. Your GitHub username

There are no wrong answers, and it's fine if you didn't finish everything. Your check-in helps us know how to support you

## Finished early, or already know the basics?

Here's how to go further this week:

1. **Add a twist** to your guessing game: limit the number of tries, keep a score, or add difficulty levels.
2. **Read ahead:** chapter 3 of the Book, which we'll cover together in week 2.
3. **Help someone** in **#ask-anything**. Explaining something is one of the best ways to really learn it.

Share what you build in **#what-im-building**

