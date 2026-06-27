# Skillforge App 📚

An Android course learning app built for the Clickretina Android Developer assessment.

## Screens

### 1. Home Screen
- Popular courses horizontal RecyclerView
- Categories horizontal RecyclerView
- Data loaded from REST API

### 2. Course Detail Screen
- Course title, rating, students, duration, level
- Instructor card with name, title, bio
- Tags chips
- Lessons list with FREE / Lock states
- Sticky bottom bar with Enroll Now button

### 3. Video Player Screen
- ExoPlayer video playback
- Seekbar with current / total time
- Lesson list with Now Playing state
- Tabs: Lessons / Notes / Resources

## Tech Stack
| Library | Purpose |
|---|---|
| Kotlin | Language |
| MVVM | Architecture |
| Retrofit + Gson | API calls |
| ExoPlayer (Media3) | Video playback |
| ViewBinding | View access |
| RecyclerView | Lists |
| ConstraintLayout | Layouts |
| LiveData + ViewModel | State management |

## API