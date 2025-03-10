### Store times avg (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| ChannelBookmarkStore.UpdateSortOrder | avg | 4ms | 7ms | 3ms | 80.63
| DraftStore.DeleteDraftsAssociatedWithPost | avg | 17ms | 28ms | 11ms | 65.23
| ChannelStore.CreateSidebarCategory | avg | 21ms | 29ms | 8ms | 39.01
| PostStore.AnalyticsPostCount | avg | 652ms | 778ms | 126ms | 19.33
| UserStore.GetAllProfilesInChannel | avg | 271ms | 312ms | 41ms | 15.10
| ChannelStore.GetMemberCount | avg | 77ms | 87ms | 10ms | 13.03
| UserStore.Search | avg | 35ms | 39ms | 4ms | 11.40
| UserStore.AutocompleteUsersInChannel | avg | 151ms | 168ms | 17ms | 11.28
| ChannelStore.GetTeamChannels | avg | 23ms | 25ms | 2ms | 8.73
| UserStore.Count | avg | 71ms | 75ms | 4ms | 5.67
| TeamStore.GetTotalMemberCount | avg | 90ms | 94ms | 4ms | 4.44
| ChannelStore.Autocomplete | avg | 964ms | 986ms | 22ms | 2.28
### Store times p99 (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| ChannelBookmarkStore.UpdateSortOrder | p99 | 5ms | 24ms | 19ms | 383.84
| PluginStore.List | p99 | 7ms | 29ms | 22ms | 305.52
| ChannelStore.CreateSidebarCategory | p99 | 25ms | 97ms | 72ms | 289.74
| RoleStore.ChannelHigherScopedPermissions | p99 | 8ms | 29ms | 21ms | 267.17
| ChannelStore.UpdateSidebarCategories | p99 | 50ms | 164ms | 114ms | 229.15
| PostStore.GetPostReminderMetadata | p99 | 5ms | 15ms | 10ms | 202.02
| UserStore.GetByUsername | p99 | 9ms | 23ms | 14ms | 159.27
| ChannelStore.GetAllChannelMembersForUser | p99 | 11ms | 28ms | 17ms | 155.42
| StatusStore.GetByIds | p99 | 10ms | 23ms | 13ms | 134.18
| DraftStore.GetDraftsForUser | p99 | 9ms | 20ms | 11ms | 120.27
| ChannelStore.SearchGroupChannels | p99 | 9ms | 20ms | 11ms | 115.81
| SessionStore.Remove | p99 | 9ms | 19ms | 10ms | 114.94
| ThreadStore.MarkAllAsReadByTeam | p99 | 5ms | 10ms | 5ms | 101.01
| TokenStore.Cleanup | p99 | 5ms | 10ms | 5ms | 100.97
| ReactionStore.GetForPost | p99 | 9ms | 18ms | 9ms | 95.08
| DraftStore.Get | p99 | 9ms | 18ms | 9ms | 95.00
| BotStore.Get | p99 | 10ms | 19ms | 9ms | 94.41
| ChannelStore.GetPublicChannelsForTeam | p99 | 25ms | 47ms | 22ms | 88.24
| ChannelStore.GetMemberForPost | p99 | 9ms | 17ms | 8ms | 86.21
| ProductNoticesStore.View | p99 | 99ms | 183ms | 84ms | 84.48
| ThreadStore.GetThreadsForUser | p99 | 10ms | 18ms | 8ms | 82.22
| ChannelStore.Get | p99 | 10ms | 18ms | 8ms | 82.11
| UserStore.GetProfilesInChannel | p99 | 5ms | 9ms | 4ms | 80.81
| ChannelBookmarkStore.Get | p99 | 5ms | 9ms | 4ms | 80.81
| EmojiStore.GetMultipleByName | p99 | 5ms | 9ms | 4ms | 80.81
| JobStore.UpdateStatus | p99 | 9ms | 16ms | 7ms | 80.00
| ChannelStore.GetMembersForUser | p99 | 9ms | 16ms | 7ms | 76.65
| DraftStore.DeleteDraftsAssociatedWithPost | p99 | 49ms | 86ms | 37ms | 76.03
| ChannelStore.GetChannels | p99 | 9ms | 16ms | 7ms | 74.52
| PostStore.Delete | p99 | 25ms | 43ms | 18ms | 72.43
| PostStore.GetPostsBefore | p99 | 11ms | 19ms | 8ms | 72.05
| UserStore.GetProfileByIds | p99 | 10ms | 17ms | 7ms | 71.04
| DraftStore.Delete | p99 | 9ms | 15ms | 6ms | 63.45
| RoleStore.GetByNames | p99 | 5ms | 8ms | 3ms | 60.61
| PreferenceStore.Get | p99 | 10ms | 16ms | 6ms | 60.60
| ChannelStore.GetSidebarCategory | p99 | 10ms | 16ms | 6ms | 60.37
| ChannelStore.IsReadOnlyChannel | p99 | 5ms | 8ms | 3ms | 60.06
| UserStore.GetProfilesByUsernames | p99 | 9ms | 14ms | 5ms | 57.01
| ThreadStore.GetThreadForUser | p99 | 15ms | 23ms | 8ms | 54.15
| ChannelStore.GetFileCount | p99 | 14ms | 21ms | 7ms | 50.83
| ThreadStore.GetThreadFollowers | p99 | 10ms | 15ms | 5ms | 50.58
| ChannelStore.IncrementMentionCount | p99 | 10ms | 15ms | 5ms | 49.98
| FileInfoStore.Get | p99 | 8ms | 12ms | 4ms | 48.80
| ChannelStore.GetGuestCount | p99 | 13ms | 19ms | 6ms | 46.70
| DraftStore.Upsert | p99 | 13ms | 19ms | 6ms | 45.65
| TeamStore.GetChannelUnreadsForAllTeams | p99 | 9ms | 13ms | 4ms | 43.65
| PostStore.GetEtag | p99 | 16ms | 23ms | 7ms | 42.66
| ChannelStore.GetChannelsByUser | p99 | 7ms | 10ms | 3ms | 42.21
| UserStore.GetAllProfilesInChannel | p99 | 643ms | 906ms | 263ms | 40.91
| UserAccessTokenStore.GetByToken | p99 | 5ms | 7ms | 2ms | 40.40
| ThreadStore.GetTotalUnreadMentions | p99 | 14ms | 19ms | 5ms | 37.01
| GroupStore.GetGroups | p99 | 11ms | 15ms | 4ms | 36.91
| StatusStore.Get | p99 | 9ms | 12ms | 3ms | 34.99
| EmojiStore.GetByName | p99 | 6ms | 8ms | 2ms | 34.97
| UserStore.GetForLogin | p99 | 9ms | 12ms | 3ms | 33.63
| FileInfoStore.SetContent | p99 | 24ms | 32ms | 8ms | 33.20
| ThreadStore.UpdateMembership | p99 | 10ms | 13ms | 3ms | 30.51
| SessionStore.GetSessionsWithActiveDeviceIds | p99 | 10ms | 13ms | 3ms | 30.35
| ThreadStore.MarkAsRead | p99 | 10ms | 13ms | 3ms | 30.30
| SharedChannelStore.HasChannel | p99 | 7ms | 9ms | 2ms | 30.29
| UserStore.Update | p99 | 25ms | 32ms | 7ms | 28.17
| ChannelBookmarkStore.GetBookmarksForChannelSince | p99 | 7ms | 9ms | 2ms | 27.85
| PostStore.GetSingle | p99 | 7ms | 9ms | 2ms | 27.36
| PostStore.GetPostsByThread | p99 | 7ms | 9ms | 2ms | 27.26
| ChannelStore.GetChannelUnread | p99 | 7ms | 9ms | 2ms | 27.16
| ChannelStore.GetChannelsWithUnreadsAndWithMentions | p99 | 7ms | 9ms | 2ms | 26.68
| FileInfoStore.GetForPost | p99 | 8ms | 10ms | 2ms | 25.12
| JobStore.UpdateOptimistically | p99 | 8ms | 10ms | 2ms | 24.62
| ThreadStore.GetTotalUnreadThreads | p99 | 8ms | 10ms | 2ms | 23.97
| ThreadStore.GetTotalThreads | p99 | 8ms | 10ms | 2ms | 23.74
| ThreadStore.GetMembershipForUser | p99 | 9ms | 11ms | 2ms | 23.00
| PostStore.GetPostIdBeforeTime | p99 | 9ms | 11ms | 2ms | 21.20
| ThreadStore.GetTeamsUnreadForUser | p99 | 10ms | 12ms | 2ms | 20.92
| StatusStore.UpdateLastActivityAt | p99 | 10ms | 12ms | 2ms | 20.54
| PostStore.SearchPostsForUser | p99 | 246ms | 296ms | 50ms | 20.32
| UserStore.GetAllProfiles | p99 | 10ms | 12ms | 2ms | 20.25
| PostStore.Get | p99 | 20ms | 24ms | 4ms | 19.66
| ChannelStore.SaveMember | p99 | 68ms | 81ms | 13ms | 19.18
| PostStore.GetPostsSince | p99 | 48ms | 57ms | 9ms | 18.82
| SessionStore.Get | p99 | 22ms | 26ms | 4ms | 17.82
| WebhookStore.GetOutgoingByTeam | p99 | 37ms | 43ms | 6ms | 16.08
| TeamStore.SaveMember | p99 | 127ms | 146ms | 19ms | 14.97
| UserStore.AutocompleteUsersInChannel | p99 | 377ms | 433ms | 56ms | 14.86
| ClusterDiscoveryStore.SetLastPingAt | p99 | 27ms | 31ms | 4ms | 14.68
| UserStore.UpdateFailedPasswordAttempts | p99 | 19ms | 21ms | 2ms | 10.54
| FileInfoStore.AttachToPost | p99 | 20ms | 22ms | 2ms | 9.96
| ChannelStore.GetByName | p99 | 34ms | 37ms | 3ms | 8.81
| UserStore.Count | p99 | 224ms | 238ms | 14ms | 6.24
| ChannelStore.CreateDirectChannel | p99 | 57ms | 59ms | 2ms | 3.49
| UserStore.Save | p99 | 166ms | 170ms | 4ms | 2.40
| ChannelStore.GetMemberCount | p99 | 247ms | 250ms | 3ms | 1.21
### Store times avg (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| ChannelStore.GetChannelsByIds | avg | 2ms | 0s | -2ms | -125.31
| TeamStore.GetMany | avg | 2ms | 0s | -2ms | -123.27
| PostStore.GetPostsByIds | avg | 2ms | 0s | -2ms | -111.33
| PostPersistentNotificationStore.UpdateLastActivity | avg | 3ms | 0s | -3ms | -87.32
| PostStore.SearchPostsForUser | avg | 70ms | 39ms | -31ms | -44.37
| StatusStore.SaveOrUpdate | avg | 12ms | 7ms | -5ms | -42.20
| PostStore.SetPostReminder | avg | 9ms | 7ms | -2ms | -22.37
| StatusStore.UpdateExpiredDNDStatuses | avg | 9ms | 7ms | -2ms | -22.18
| ChannelStore.AutocompleteInTeamForSearch | avg | 168ms | 135ms | -33ms | -19.66
| ChannelStore.GetAllChannelMembersNotifyPropsForChannel | avg | 12ms | 10ms | -2ms | -16.46
| PostStore.Update | avg | 16ms | 14ms | -2ms | -12.74
| TeamStore.GetActiveMemberCount | avg | 124ms | 122ms | -2ms | -1.62
### Store times p99 (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| ChannelStore.GetChannelsByIds | p99 | 5ms | 0s | -5ms | -101.01
| TeamStore.GetMany | p99 | 5ms | 0s | -5ms | -101.01
| PostPersistentNotificationStore.UpdateLastActivity | p99 | 5ms | 0s | -5ms | -101.01
| PostStore.GetPostsByIds | p99 | 5ms | 0s | -5ms | -101.01
| StatusStore.UpdateExpiredDNDStatuses | p99 | 86ms | 10ms | -76ms | -87.86
| ScheduledPostStore.GetPendingScheduledPosts | p99 | 43ms | 9ms | -34ms | -78.61
| ScheduledPostStore.UpdateOldScheduledPosts | p99 | 21ms | 5ms | -16ms | -76.37
| JobStore.GetCountByStatusAndType | p99 | 62ms | 24ms | -38ms | -61.79
| StatusStore.SaveOrUpdate | p99 | 227ms | 87ms | -140ms | -61.68
| UserStore.GetMany | p99 | 17ms | 8ms | -9ms | -52.32
| ChannelStore.GetMembers | p99 | 10ms | 5ms | -5ms | -51.81
| PostStore.GetPostReminders | p99 | 43ms | 24ms | -19ms | -43.93
| JobStore.GetNewestJobByStatusesAndType | p99 | 13ms | 8ms | -5ms | -37.17
| JobStore.Save | p99 | 14ms | 9ms | -5ms | -36.36
| PostStore.Update | p99 | 34ms | 25ms | -9ms | -26.66
| PostPersistentNotificationStore.DeleteExpired | p99 | 8ms | 6ms | -2ms | -25.97
| PostAcknowledgementStore.GetForPost | p99 | 9ms | 7ms | -2ms | -22.65
| PostPersistentNotificationStore.Get | p99 | 17ms | 14ms | -3ms | -17.44
| JobStore.GetAllByStatus | p99 | 25ms | 22ms | -3ms | -12.23
| ChannelStore.AutocompleteInTeamForSearch | p99 | 2.041s | 1.828s | -213ms | -10.43
| PreferenceStore.DeleteCategoryAndName | p99 | 23ms | 21ms | -2ms | -8.85
| ChannelStore.GetAllChannelMembersNotifyPropsForChannel | p99 | 94ms | 90ms | -4ms | -4.28
### API times avg (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| deleteChannelBookmark | avg | 11ms | 21ms | 10ms | 91.61
| updateChannelBookmarkSortOrder | avg | 6ms | 11ms | 5ms | 89.95
| createCategoryForTeamForUser | avg | 23ms | 32ms | 9ms | 39.83
| removeUserCustomStatus | avg | 104ms | 141ms | 37ms | 35.75
| createChannel | avg | 189ms | 250ms | 61ms | 32.36
| createDirectChannel | avg | 170ms | 211ms | 41ms | 24.12
| createGroupChannel | avg | 252ms | 303ms | 51ms | 20.20
| createUser | avg | 131ms | 148ms | 17ms | 12.98
| autocompleteUsers | avg | 122ms | 137ms | 15ms | 12.33
| addChannelMember | avg | 164ms | 183ms | 19ms | 11.57
| searchUsers | avg | 36ms | 40ms | 4ms | 11.08
| getPostsForChannel | avg | 23ms | 25ms | 2ms | 8.76
| uploadFileStream | avg | 363ms | 394ms | 31ms | 8.55
| createPost | avg | 248ms | 266ms | 18ms | 7.25
| addTeamMember | avg | 724ms | 767ms | 43ms | 5.94
| login | avg | 67ms | 71ms | 4ms | 5.93
| searchAllChannels | avg | 965ms | 986ms | 21ms | 2.18
### API times p99 (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| createCategoryForTeamForUser | p99 | 25ms | 97ms | 72ms | 289.74
| updateChannelBookmarkSortOrder | p99 | 10ms | 25ms | 15ms | 150.75
| getDrafts | p99 | 9ms | 21ms | 12ms | 126.46
| searchGroupChannels | p99 | 10ms | 20ms | 10ms | 105.13
| updateReadStateAllThreadsByUser | p99 | 5ms | 10ms | 5ms | 101.01
| deleteDraft | p99 | 10ms | 19ms | 9ms | 90.45
| getPublicChannelsForTeam | p99 | 25ms | 47ms | 22ms | 88.24
| createGroupChannel | p99 | 495ms | 904ms | 409ms | 82.65
| removeUserCustomStatus | p99 | 250ms | 456ms | 206ms | 82.41
| getThreadsForUser | p99 | 10ms | 18ms | 8ms | 81.06
| getChannelMembersForTeamForUser | p99 | 10ms | 17ms | 7ms | 70.19
| getPostThread | p99 | 29ms | 49ms | 20ms | 69.94
| getUsersByNames | p99 | 9ms | 15ms | 6ms | 66.82
| updateCategoriesForTeamForUser | p99 | 99ms | 164ms | 65ms | 65.95
| getTeamMember | p99 | 12ms | 19ms | 7ms | 59.25
| getChannelsForTeamForUser | p99 | 12ms | 18ms | 6ms | 49.14
| updateReadStateThreadByUser | p99 | 60ms | 87ms | 27ms | 45.00
| saveReaction | p99 | 24ms | 34ms | 10ms | 40.99
| getChannelsForUser | p99 | 7ms | 10ms | 3ms | 40.56
| searchPostsInTeam | p99 | 318ms | 430ms | 112ms | 35.24
| getTeamMembersForUser | p99 | 14ms | 18ms | 4ms | 29.49
| updatePreferences | p99 | 25ms | 32ms | 7ms | 28.16
| getAllTeams | p99 | 13ms | 16ms | 3ms | 22.49
| upsertDraft | p99 | 18ms | 22ms | 4ms | 22.19
| autocompleteUsers | p99 | 339ms | 414ms | 75ms | 22.14
| viewChannel | p99 | 41ms | 49ms | 8ms | 19.73
| getUsers | p99 | 18ms | 21ms | 3ms | 16.83
| getTeamsUnreadForUser | p99 | 19ms | 22ms | 3ms | 16.15
| createUser | p99 | 429ms | 472ms | 43ms | 10.01
| getPostsForChannel | p99 | 200ms | 216ms | 16ms | 7.99
| createChannel | p99 | 468ms | 494ms | 26ms | 5.56
| createDirectChannel | p99 | 473ms | 496ms | 23ms | 4.86
| getPostsForChannelAroundLastUnread | p99 | 65ms | 68ms | 3ms | 4.65
| addChannelMember | p99 | 464ms | 481ms | 17ms | 3.66
| getFilePreview | p99 | 96ms | 98ms | 2ms | 2.09
| addTeamMember | p99 | 2.4s | 2.432s | 32ms | 1.33
| createPost | p99 | 967ms | 979ms | 12ms | 1.24
### API times avg (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| getChannelMembers | avg | 5ms | 3ms | -2ms | -44.04
| searchPostsInTeam | avg | 75ms | 45ms | -30ms | -39.80
| createEmoji | avg | 9ms | 7ms | -2ms | -21.08
| autocompleteChannelsForTeamForSearch | avg | 168ms | 135ms | -33ms | -19.65
| getProfileImage | avg | 75ms | 66ms | -9ms | -12.05
| setPostReminder | avg | 18ms | 16ms | -2ms | -10.84
| createChannelBookmark | avg | 22ms | 20ms | -2ms | -9.15
| patchPost | avg | 29ms | 27ms | -2ms | -6.80
| getTeamStats | avg | 124ms | 122ms | -2ms | -1.62
### API times p99 (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| logout | p99 | 211ms | 94ms | -117ms | -55.45
| getChannelMembers | p99 | 10ms | 5ms | -5ms | -50.89
| createChannelBookmark | p99 | 94ms | 48ms | -46ms | -49.19
| setPostReminder | p99 | 48ms | 25ms | -23ms | -48.29
| patchPost | p99 | 84ms | 50ms | -34ms | -40.48
| getChannel | p99 | 33ms | 21ms | -12ms | -36.50
| unfollowThreadByUser | p99 | 53ms | 40ms | -13ms | -24.53
| getProfileImage | p99 | 309ms | 276ms | -33ms | -10.68
| autocompleteChannelsForTeamForSearch | p99 | 2.041s | 1.828s | -213ms | -10.43
### Store times:
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| AuditStore.Save |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 19ms| 20ms | 1ms | 5.254
| BotStore.Get |  Avg| 3ms| 2ms | -1ms | -39.409
| |  P99| 10ms| 19ms | 9ms | 94.406
| ChannelBookmarkStore.Delete |  Avg| 7ms| 6ms | -1ms | -14.616
| |  P99| 10ms| 10ms | 0s | 0.000
| ChannelBookmarkStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 9ms | 4ms | 80.808
| ChannelBookmarkStore.GetBookmarksForChannelSince |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 7ms| 9ms | 2ms | 27.853
| ChannelBookmarkStore.Save |  Avg| 11ms| 12ms | 1ms | 9.104
| |  P99| 25ms| 25ms | 0s | 0.000
| ChannelBookmarkStore.UpdateSortOrder |  Avg| 4ms| 7ms | 3ms | 80.631
| |  P99| 5ms| 24ms | 19ms | 383.838
| ChannelMemberHistoryStore.LogJoinEvent |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 15ms| 14ms | -1ms | -6.813
| ChannelStore.Autocomplete |  Avg| 964ms| 986ms | 22ms | 2.281
| |  P99| 2.462s| 2.47s | 8ms | 0.325
| ChannelStore.AutocompleteInTeamForSearch |  Avg| 168ms| 135ms | -33ms | -19.662
| |  P99| 2.041s| 1.828s | -213ms | -10.434
| ChannelStore.CreateDirectChannel |  Avg| 22ms| 21ms | -1ms | -4.607
| |  P99| 57ms| 59ms | 2ms | 3.488
| ChannelStore.CreateInitialSidebarCategories |  Avg| 21ms| 20ms | -1ms | -4.857
| |  P99| 50ms| 50ms | 0s | 0.000
| ChannelStore.CreateSidebarCategory |  Avg| 21ms| 29ms | 8ms | 39.008
| |  P99| 25ms| 97ms | 72ms | 289.738
| ChannelStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 10ms| 18ms | 8ms | 82.109
| ChannelStore.GetAllChannelMembersForUser |  Avg| 2ms| 3ms | 1ms | 42.311
| |  P99| 11ms| 28ms | 17ms | 155.420
| ChannelStore.GetAllChannelMembersNotifyPropsForChannel |  Avg| 12ms| 10ms | -2ms | -16.456
| |  P99| 94ms| 90ms | -4ms | -4.277
| ChannelStore.GetByName |  Avg| 4ms| 5ms | 1ms | 24.330
| |  P99| 34ms| 37ms | 3ms | 8.807
| ChannelStore.GetChannelUnread |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 7ms| 9ms | 2ms | 27.164
| ChannelStore.GetChannels |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 9ms| 16ms | 7ms | 74.521
| ChannelStore.GetChannelsByIds |  Avg| 2ms| 0s | -2ms | -125.312
| |  P99| 5ms| 0s | -5ms | -101.010
| ChannelStore.GetChannelsByUser |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 7ms| 10ms | 3ms | 42.213
| ChannelStore.GetChannelsWithUnreadsAndWithMentions |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 7ms| 9ms | 2ms | 26.683
| ChannelStore.GetFileCount |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 14ms| 21ms | 7ms | 50.827
| ChannelStore.GetGuestCount |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 13ms| 19ms | 6ms | 46.703
| ChannelStore.GetMember |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 18ms| 18ms | 0s | 0.000
| ChannelStore.GetMemberCount |  Avg| 77ms| 87ms | 10ms | 13.028
| |  P99| 247ms| 250ms | 3ms | 1.212
| ChannelStore.GetMemberForPost |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 9ms| 17ms | 8ms | 86.210
| ChannelStore.GetMemberLastViewedAt |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 8ms| 9ms | 1ms | 11.971
| ChannelStore.GetMembers |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 10ms| 5ms | -5ms | -51.814
| ChannelStore.GetMembersForUser |  Avg| 2ms| 3ms | 1ms | 43.230
| |  P99| 9ms| 16ms | 7ms | 76.655
| ChannelStore.GetPinnedPostCount |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 8ms| 9ms | 1ms | 12.973
| ChannelStore.GetPublicChannelsForTeam |  Avg| 11ms| 10ms | -1ms | -8.922
| |  P99| 25ms| 47ms | 22ms | 88.244
| ChannelStore.GetSidebarCategoriesForTeamForUser |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 23ms| 24ms | 1ms | 4.274
| ChannelStore.GetSidebarCategory |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 10ms| 16ms | 6ms | 60.365
| ChannelStore.GetTeamChannels |  Avg| 23ms| 25ms | 2ms | 8.732
| |  P99| 48ms| 49ms | 1ms | 2.066
| ChannelStore.IncrementMentionCount |  Avg| 2ms| 3ms | 1ms | 40.814
| |  P99| 10ms| 15ms | 5ms | 49.982
| ChannelStore.IsReadOnlyChannel |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 8ms | 3ms | 60.056
| ChannelStore.Save |  Avg| 13ms| 14ms | 1ms | 7.469
| |  P99| 49ms| 50ms | 1ms | 2.023
| ChannelStore.SaveMember |  Avg| 25ms| 26ms | 1ms | 3.955
| |  P99| 68ms| 81ms | 13ms | 19.177
| ChannelStore.SearchGroupChannels |  Avg| 2ms| 3ms | 1ms | 42.581
| |  P99| 9ms| 20ms | 11ms | 115.807
| ChannelStore.UpdateLastViewedAt |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 21ms| 22ms | 1ms | 4.831
| ChannelStore.UpdateSidebarCategories |  Avg| 35ms| 36ms | 1ms | 2.890
| |  P99| 50ms| 164ms | 114ms | 229.146
| ChannelStore.UpdateSidebarChannelsByPreferences |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 8ms| 8ms | 0s | 0.000
| ClusterDiscoveryStore.SetLastPingAt |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 27ms| 31ms | 4ms | 14.678
| CommandWebhookStore.Cleanup |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| DesktopTokensStore.DeleteOlderThan |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| DraftStore.Delete |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 9ms| 15ms | 6ms | 63.446
| DraftStore.DeleteDraftsAssociatedWithPost |  Avg| 17ms| 28ms | 11ms | 65.233
| |  P99| 49ms| 86ms | 37ms | 76.027
| DraftStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 9ms| 18ms | 9ms | 95.000
| DraftStore.GetDraftsForUser |  Avg| 2ms| 3ms | 1ms | 44.349
| |  P99| 9ms| 20ms | 11ms | 120.270
| DraftStore.Upsert |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 13ms| 19ms | 6ms | 45.646
| EmojiStore.GetByName |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 6ms| 8ms | 2ms | 34.972
| EmojiStore.GetMultipleByName |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 9ms | 4ms | 80.808
| FileInfoStore.AttachToPost |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 20ms| 22ms | 2ms | 9.956
| FileInfoStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 8ms| 12ms | 4ms | 48.798
| FileInfoStore.GetByIds |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 9ms| 9ms | 0s | 0.000
| FileInfoStore.GetForPost |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 8ms| 10ms | 2ms | 25.119
| FileInfoStore.Save |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 19ms| 20ms | 1ms | 5.403
| FileInfoStore.SetContent |  Avg| 9ms| 9ms | 0s | 0.000
| |  P99| 24ms| 32ms | 8ms | 33.203
| GroupStore.AdminRoleGroupsForSyncableMember |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 8ms| 9ms | 1ms | 12.447
| GroupStore.GetByName |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 9ms| 10ms | 1ms | 10.695
| GroupStore.GetGroups |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 11ms| 15ms | 4ms | 36.911
| JobStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| JobStore.GetAllByStatus |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 25ms| 22ms | -3ms | -12.226
| JobStore.GetCountByStatusAndType |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 62ms| 24ms | -38ms | -61.789
| JobStore.GetNewestJobByStatusesAndType |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 13ms| 8ms | -5ms | -37.175
| JobStore.Save |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 14ms| 9ms | -5ms | -36.364
| JobStore.UpdateOptimistically |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 8ms| 10ms | 2ms | 24.615
| JobStore.UpdateStatus |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 9ms| 16ms | 7ms | 80.000
| JobStore.UpdateStatusOptimistically |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 10ms| 10ms | 0s | 0.000
| LinkMetadataStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 8ms| 9ms | 1ms | 12.683
| LinkMetadataStore.Save |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 9ms| 9ms | 0s | 0.000
| PluginStore.Delete |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 9ms| 9ms | 0s | 0.000
| PluginStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PluginStore.List |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 7ms| 29ms | 22ms | 305.521
| PluginStore.SetWithOptions |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 21ms| 21ms | 0s | 0.000
| PostAcknowledgementStore.GetForPost |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 9ms| 7ms | -2ms | -22.647
| PostAcknowledgementStore.GetForPosts |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 22ms| 23ms | 1ms | 4.611
| PostPersistentNotificationStore.DeleteExpired |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 8ms| 6ms | -2ms | -25.974
| PostPersistentNotificationStore.Get |  Avg| 3ms| 2ms | -1ms | -39.765
| |  P99| 17ms| 14ms | -3ms | -17.442
| PostPersistentNotificationStore.GetSingle |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 7ms| 8ms | 1ms | 15.276
| PostPersistentNotificationStore.UpdateLastActivity |  Avg| 3ms| 0s | -3ms | -87.321
| |  P99| 5ms| 0s | -5ms | -101.010
| PostPriorityStore.GetForPost |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 9ms| 10ms | 1ms | 11.532
| PostPriorityStore.GetForPosts |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 22ms| 23ms | 1ms | 4.562
| PostStore.AnalyticsPostCount |  Avg| 652ms| 778ms | 126ms | 19.335
| |  P99| 995ms| 995ms | 0s | 0.000
| PostStore.Delete |  Avg| 15ms| 16ms | 1ms | 6.797
| |  P99| 25ms| 43ms | 18ms | 72.435
| PostStore.Get |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 20ms| 24ms | 4ms | 19.659
| PostStore.GetEtag |  Avg| 2ms| 3ms | 1ms | 43.451
| |  P99| 16ms| 23ms | 7ms | 42.661
| PostStore.GetMaxPostSize |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.GetPostIdAfterTime |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 9ms| 9ms | 0s | 0.000
| PostStore.GetPostIdBeforeTime |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 9ms| 11ms | 2ms | 21.205
| PostStore.GetPostReminderMetadata |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 15ms | 10ms | 202.020
| PostStore.GetPostReminders |  Avg| 9ms| 8ms | -1ms | -11.348
| |  P99| 43ms| 24ms | -19ms | -43.931
| PostStore.GetPosts |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 21ms| 20ms | -1ms | -4.777
| PostStore.GetPostsAfter |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 10ms| 9ms | -1ms | -10.427
| PostStore.GetPostsBefore |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 11ms| 19ms | 8ms | 72.047
| PostStore.GetPostsByIds |  Avg| 2ms| 0s | -2ms | -111.331
| |  P99| 5ms| 0s | -5ms | -101.010
| PostStore.GetPostsByThread |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 7ms| 9ms | 2ms | 27.258
| PostStore.GetPostsSince |  Avg| 9ms| 10ms | 1ms | 11.424
| |  P99| 48ms| 57ms | 9ms | 18.824
| PostStore.GetSingle |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 7ms| 9ms | 2ms | 27.358
| PostStore.InvalidateLastPostTimeCache |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.Save |  Avg| 13ms| 13ms | 0s | 0.000
| |  P99| 49ms| 49ms | 0s | 0.000
| PostStore.SearchPostsForUser |  Avg| 70ms| 39ms | -31ms | -44.370
| |  P99| 246ms| 296ms | 50ms | 20.318
| PostStore.SetPostReminder |  Avg| 9ms| 7ms | -2ms | -22.372
| |  P99| 24ms| 23ms | -1ms | -4.117
| PostStore.Update |  Avg| 16ms| 14ms | -2ms | -12.737
| |  P99| 34ms| 25ms | -9ms | -26.662
| PreferenceStore.DeleteCategoryAndName |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 23ms| 21ms | -2ms | -8.849
| PreferenceStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 10ms| 16ms | 6ms | 60.600
| PreferenceStore.GetAll |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 19ms| 20ms | 1ms | 5.258
| PreferenceStore.Save |  Avg| 10ms| 10ms | 0s | 0.000
| |  P99| 35ms| 35ms | 0s | 0.000
| ProductNoticesStore.ClearOldNotices |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ProductNoticesStore.View |  Avg| 36ms| 37ms | 1ms | 2.794
| |  P99| 99ms| 183ms | 84ms | 84.478
| ReactionStore.GetForPost |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 9ms| 18ms | 9ms | 95.079
| RoleStore.ChannelHigherScopedPermissions |  Avg| 2ms| 3ms | 1ms | 55.740
| |  P99| 8ms| 29ms | 21ms | 267.167
| RoleStore.GetByNames |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 8ms | 3ms | 60.606
| ScheduledPostStore.GetPendingScheduledPosts |  Avg| 3ms| 2ms | -1ms | -29.035
| |  P99| 43ms| 9ms | -34ms | -78.613
| ScheduledPostStore.UpdateOldScheduledPosts |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 21ms| 5ms | -16ms | -76.372
| SessionStore.Get |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 22ms| 26ms | 4ms | 17.822
| SessionStore.GetLRUSessions |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 8ms| 9ms | 1ms | 11.996
| SessionStore.GetSessionsExpired |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| SessionStore.GetSessionsWithActiveDeviceIds |  Avg| 2ms| 3ms | 1ms | 41.481
| |  P99| 10ms| 13ms | 3ms | 30.346
| SessionStore.Remove |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 9ms| 19ms | 10ms | 114.945
| SessionStore.Save |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 21ms| 22ms | 1ms | 4.656
| SessionStore.UpdateLastActivityAt |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 10ms| 10ms | 0s | 0.000
| SharedChannelStore.HasChannel |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 7ms| 9ms | 2ms | 30.288
| StatusStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 9ms| 12ms | 3ms | 34.986
| StatusStore.GetByIds |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 10ms| 23ms | 13ms | 134.180
| StatusStore.SaveOrUpdate |  Avg| 12ms| 7ms | -5ms | -42.199
| |  P99| 227ms| 87ms | -140ms | -61.681
| StatusStore.UpdateExpiredDNDStatuses |  Avg| 9ms| 7ms | -2ms | -22.180
| |  P99| 86ms| 10ms | -76ms | -87.861
| StatusStore.UpdateLastActivityAt |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 10ms| 12ms | 2ms | 20.540
| SystemStore.GetByName |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 8ms| 9ms | 1ms | 11.946
| TeamStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 7ms| 8ms | 1ms | 15.289
| TeamStore.GetActiveMemberCount |  Avg| 124ms| 122ms | -2ms | -1.617
| |  P99| 249ms| 249ms | 0s | 0.000
| TeamStore.GetAllPage |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 9ms| 10ms | 1ms | 10.764
| TeamStore.GetChannelUnreadsForAllTeams |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 9ms| 13ms | 4ms | 43.653
| TeamStore.GetMany |  Avg| 2ms| 0s | -2ms | -123.271
| |  P99| 5ms| 0s | -5ms | -101.010
| TeamStore.GetMember |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 10ms| 10ms | 0s | 0.000
| TeamStore.GetTeamsByUserId |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 9ms| 9ms | 0s | 0.000
| TeamStore.GetTeamsForUser |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 9ms| 10ms | 1ms | 11.447
| TeamStore.GetTotalMemberCount |  Avg| 90ms| 94ms | 4ms | 4.439
| |  P99| 244ms| 242ms | -2ms | -0.821
| TeamStore.SaveMember |  Avg| 73ms| 74ms | 1ms | 1.371
| |  P99| 127ms| 146ms | 19ms | 14.969
| ThreadStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 7ms| 8ms | 1ms | 13.986
| ThreadStore.GetMembershipForUser |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 9ms| 11ms | 2ms | 23.003
| ThreadStore.GetTeamsUnreadForUser |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 10ms| 12ms | 2ms | 20.916
| ThreadStore.GetThreadFollowers |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 10ms| 15ms | 5ms | 50.584
| ThreadStore.GetThreadForUser |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 15ms| 23ms | 8ms | 54.152
| ThreadStore.GetThreadUnreadReplyCount |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 8ms| 9ms | 1ms | 12.849
| ThreadStore.GetThreadsForUser |  Avg| 2ms| 3ms | 1ms | 40.039
| |  P99| 10ms| 18ms | 8ms | 82.217
| ThreadStore.GetTotalThreads |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 8ms| 10ms | 2ms | 23.739
| ThreadStore.GetTotalUnreadMentions |  Avg| 2ms| 3ms | 1ms | 42.347
| |  P99| 14ms| 19ms | 5ms | 37.014
| ThreadStore.GetTotalUnreadThreads |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 8ms| 10ms | 2ms | 23.968
| ThreadStore.GetTotalUnreadUrgentMentions |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 9ms| 10ms | 1ms | 11.541
| ThreadStore.MaintainMembership |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 23ms| 24ms | 1ms | 4.342
| ThreadStore.MarkAllAsReadByChannels |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 8ms| 9ms | 1ms | 12.905
| ThreadStore.MarkAllAsReadByTeam |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 5ms| 10ms | 5ms | 101.010
| ThreadStore.MarkAsRead |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 10ms| 13ms | 3ms | 30.302
| ThreadStore.UpdateMembership |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 10ms| 13ms | 3ms | 30.512
| TokenStore.Cleanup |  Avg| 2ms| 3ms | 1ms | 48.516
| |  P99| 5ms| 10ms | 5ms | 100.974
| UserAccessTokenStore.GetByToken |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 7ms | 2ms | 40.404
| UserStore.AutocompleteUsersInChannel |  Avg| 151ms| 168ms | 17ms | 11.279
| |  P99| 377ms| 433ms | 56ms | 14.859
| UserStore.Count |  Avg| 71ms| 75ms | 4ms | 5.669
| |  P99| 224ms| 238ms | 14ms | 6.236
| UserStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 9ms| 10ms | 1ms | 11.661
| UserStore.GetAllProfiles |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 10ms| 12ms | 2ms | 20.248
| UserStore.GetAllProfilesInChannel |  Avg| 271ms| 312ms | 41ms | 15.104
| |  P99| 643ms| 906ms | 263ms | 40.906
| UserStore.GetByUsername |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 9ms| 23ms | 14ms | 159.265
| UserStore.GetForLogin |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 9ms| 12ms | 3ms | 33.631
| UserStore.GetMany |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 17ms| 8ms | -9ms | -52.321
| UserStore.GetProfileByIds |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 10ms| 17ms | 7ms | 71.035
| UserStore.GetProfilesByUsernames |  Avg| 2ms| 3ms | 1ms | 43.280
| |  P99| 9ms| 14ms | 5ms | 57.009
| UserStore.GetProfilesInChannel |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 9ms | 4ms | 80.808
| UserStore.GetProfilesNotInChannel |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 9ms| 9ms | 0s | 0.000
| UserStore.GetUnreadCount |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 21ms| 21ms | 0s | 0.000
| UserStore.IsEmpty |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| UserStore.Save |  Avg| 70ms| 70ms | 0s | 0.000
| |  P99| 166ms| 170ms | 4ms | 2.403
| UserStore.Search |  Avg| 35ms| 39ms | 4ms | 11.402
| |  P99| 243ms| 245ms | 2ms | 0.822
| UserStore.Update |  Avg| 7ms| 6ms | -1ms | -15.205
| |  P99| 25ms| 32ms | 7ms | 28.171
| UserStore.UpdateFailedPasswordAttempts |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 19ms| 21ms | 2ms | 10.539
| UserStore.UpdateLastLogin |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 12ms| 12ms | 0s | 0.000
| UserStore.UpdateUpdateAt |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 15ms| 15ms | 0s | 0.000
| UserTermsOfServiceStore.GetByUser |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 9ms| 9ms | 0s | 0.000
| WebhookStore.GetOutgoingByTeam |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 37ms| 43ms | 6ms | 16.084
### API times:
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| addChannelMember | Avg| 164ms| 183ms | 19ms | 11.570
| | P99| 464ms| 481ms | 17ms | 3.663
| addTeamMember | Avg| 724ms| 767ms | 43ms | 5.938
| | P99| 2.4s| 2.432s | 32ms | 1.334
| autocompleteChannelsForTeamForSearch | Avg| 168ms| 135ms | -33ms | -19.655
| | P99| 2.041s| 1.828s | -213ms | -10.434
| autocompleteUsers | Avg| 122ms| 137ms | 15ms | 12.325
| | P99| 339ms| 414ms | 75ms | 22.139
| createCategoryForTeamForUser | Avg| 23ms| 32ms | 9ms | 39.830
| | P99| 25ms| 97ms | 72ms | 289.738
| createChannel | Avg| 189ms| 250ms | 61ms | 32.358
| | P99| 468ms| 494ms | 26ms | 5.560
| createChannelBookmark | Avg| 22ms| 20ms | -2ms | -9.145
| | P99| 94ms| 48ms | -46ms | -49.194
| createDirectChannel | Avg| 170ms| 211ms | 41ms | 24.123
| | P99| 473ms| 496ms | 23ms | 4.862
| createEmoji | Avg| 9ms| 7ms | -2ms | -21.085
| | P99| 24ms| 24ms | 0s | 0.000
| createGroupChannel | Avg| 252ms| 303ms | 51ms | 20.202
| | P99| 495ms| 904ms | 409ms | 82.655
| createPost | Avg| 248ms| 266ms | 18ms | 7.253
| | P99| 967ms| 979ms | 12ms | 1.241
| createUser | Avg| 131ms| 148ms | 17ms | 12.981
| | P99| 429ms| 472ms | 43ms | 10.015
| deleteChannelBookmark | Avg| 11ms| 21ms | 10ms | 91.609
| | P99| 25ms| 25ms | 0s | 0.000
| deleteDraft | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 10ms| 19ms | 9ms | 90.445
| deletePost | Avg| 21ms| 22ms | 1ms | 4.653
| | P99| 48ms| 48ms | 0s | 0.000
| followThreadByUser | Avg| 11ms| 11ms | 0s | 0.000
| | P99| 25ms| 25ms | 0s | 0.000
| getAllTeams | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 13ms| 16ms | 3ms | 22.495
| getCategoriesForTeamForUser | Avg| 7ms| 7ms | 0s | 0.000
| | P99| 24ms| 25ms | 1ms | 4.217
| getChannel | Avg| 4ms| 5ms | 1ms | 23.150
| | P99| 33ms| 21ms | -12ms | -36.504
| getChannelMember | Avg| 4ms| 4ms | 0s | 0.000
| | P99| 24ms| 25ms | 1ms | 4.088
| getChannelMembers | Avg| 5ms| 3ms | -2ms | -44.037
| | P99| 10ms| 5ms | -5ms | -50.891
| getChannelMembersForTeamForUser | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 10ms| 17ms | 7ms | 70.192
| getChannelStats | Avg| 8ms| 8ms | 0s | 0.000
| | P99| 220ms| 219ms | -1ms | -0.455
| getChannelUnread | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 8ms| 9ms | 1ms | 13.265
| getChannelsForTeamForUser | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 12ms| 18ms | 6ms | 49.136
| getChannelsForUser | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 7ms| 10ms | 3ms | 40.562
| getClientConfig | Avg| 7ms| 7ms | 0s | 0.000
| | P99| 24ms| 25ms | 1ms | 4.108
| getDrafts | Avg| 2ms| 3ms | 1ms | 41.301
| | P99| 9ms| 21ms | 12ms | 126.460
| getFilePreview | Avg| 38ms| 39ms | 1ms | 2.615
| | P99| 96ms| 98ms | 2ms | 2.089
| getFileThumbnail | Avg| 32ms| 32ms | 0s | 0.000
| | P99| 91ms| 92ms | 1ms | 1.104
| getPostThread | Avg| 10ms| 11ms | 1ms | 9.696
| | P99| 29ms| 49ms | 20ms | 69.944
| getPostsForChannel | Avg| 23ms| 25ms | 2ms | 8.762
| | P99| 200ms| 216ms | 16ms | 7.994
| getPostsForChannelAroundLastUnread | Avg| 19ms| 20ms | 1ms | 5.175
| | P99| 65ms| 68ms | 3ms | 4.646
| getPreferences | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 19ms| 20ms | 1ms | 5.135
| getProfileImage | Avg| 75ms| 66ms | -9ms | -12.047
| | P99| 309ms| 276ms | -33ms | -10.676
| getPublicChannelsForTeam | Avg| 12ms| 11ms | -1ms | -8.190
| | P99| 25ms| 47ms | 22ms | 88.243
| getTeamMember | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 12ms| 19ms | 7ms | 59.253
| getTeamMembersForUser | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 14ms| 18ms | 4ms | 29.491
| getTeamStats | Avg| 124ms| 122ms | -2ms | -1.616
| | P99| 249ms| 249ms | 0s | 0.000
| getTeamsForUser | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 9ms| 9ms | 0s | 0.000
| getTeamsUnreadForUser | Avg| 4ms| 4ms | 0s | 0.000
| | P99| 19ms| 22ms | 3ms | 16.146
| getThreadsForUser | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 10ms| 18ms | 8ms | 81.058
| getUser | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 18ms| 19ms | 1ms | 5.710
| getUserStatus | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getUserStatusesByIds | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getUsers | Avg| 3ms| 4ms | 1ms | 28.610
| | P99| 18ms| 21ms | 3ms | 16.825
| getUsersByIds | Avg| 1ms| 1ms | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getUsersByNames | Avg| 2ms| 3ms | 1ms | 40.631
| | P99| 9ms| 15ms | 6ms | 66.819
| getWebappPlugins | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| listChannelBookmarksForChannel | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 8ms| 9ms | 1ms | 12.296
| login | Avg| 67ms| 71ms | 4ms | 5.933
| | P99| 245ms| 245ms | 0s | 0.000
| logout | Avg| 33ms| 34ms | 1ms | 3.050
| | P99| 211ms| 94ms | -117ms | -55.449
| patchPost | Avg| 29ms| 27ms | -2ms | -6.803
| | P99| 84ms| 50ms | -34ms | -40.476
| removeUserCustomStatus | Avg| 104ms| 141ms | 37ms | 35.746
| | P99| 250ms| 456ms | 206ms | 82.409
| root | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| saveReaction | Avg| 7ms| 7ms | 0s | 0.000
| | P99| 24ms| 34ms | 10ms | 40.993
| searchAllChannels | Avg| 965ms| 986ms | 21ms | 2.177
| | P99| 2.462s| 2.47s | 8ms | 0.325
| searchGroupChannels | Avg| 2ms| 3ms | 1ms | 41.396
| | P99| 10ms| 20ms | 10ms | 105.129
| searchPostsInTeam | Avg| 75ms| 45ms | -30ms | -39.801
| | P99| 318ms| 430ms | 112ms | 35.242
| searchUsers | Avg| 36ms| 40ms | 4ms | 11.083
| | P99| 244ms| 245ms | 1ms | 0.411
| setPostReminder | Avg| 18ms| 16ms | -2ms | -10.841
| | P99| 48ms| 25ms | -23ms | -48.292
| submitPerformanceReport | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| unfollowThreadByUser | Avg| 13ms| 12ms | -1ms | -7.955
| | P99| 53ms| 40ms | -13ms | -24.525
| updateCategoriesForTeamForUser | Avg| 49ms| 50ms | 1ms | 2.053
| | P99| 99ms| 164ms | 65ms | 65.948
| updateChannelBookmark | Avg| 15ms| 14ms | -1ms | -6.648
| | P99| 25ms| 25ms | 0s | 0.000
| updateChannelBookmarkSortOrder | Avg| 6ms| 11ms | 5ms | 89.954
| | P99| 10ms| 25ms | 15ms | 150.754
| updatePreferences | Avg| 10ms| 10ms | 0s | 0.000
| | P99| 25ms| 32ms | 7ms | 28.164
| updateReadStateAllThreadsByUser | Avg| 4ms| 4ms | 0s | 0.000
| | P99| 5ms| 10ms | 5ms | 101.010
| updateReadStateThreadByUser | Avg| 24ms| 25ms | 1ms | 4.120
| | P99| 60ms| 87ms | 27ms | 45.005
| updateUserCustomStatus | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| uploadFileStream | Avg| 363ms| 394ms | 31ms | 8.546
| | P99| 981ms| 985ms | 4ms | 0.408
| upsertDraft | Avg| 4ms| 4ms | 0s | 0.000
| | P99| 18ms| 22ms | 4ms | 22.189
| viewChannel | Avg| 13ms| 13ms | 0s | 0.000
| | P99| 41ms| 49ms | 8ms | 19.732
