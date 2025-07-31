### Store times avg (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| EmojiStore.GetMultipleByName | avg | 1ms | 4ms | 3ms | 350.64
| ScheduledPostStore.GetPendingScheduledPosts | avg | 1ms | 3ms | 2ms | 219.85
| SessionStore.Get | avg | 6ms | 8ms | 2ms | 30.80
| DraftStore.DeleteDraftsAssociatedWithPost | avg | 7ms | 9ms | 2ms | 27.29
| JobStore.UpdateStatusOptimistically | avg | 7ms | 9ms | 2ms | 26.97
| ChannelStore.GetAllChannelMembersNotifyPropsForChannel | avg | 11ms | 13ms | 2ms | 17.71
| ChannelStore.Save | avg | 12ms | 14ms | 2ms | 16.15
| ChannelStore.SaveMember | avg | 32ms | 35ms | 3ms | 9.52
| UserStore.GetAllProfilesInChannel | avg | 264ms | 287ms | 23ms | 8.70
| UserStore.Count | avg | 104ms | 113ms | 9ms | 8.66
| TeamStore.GetTotalMemberCount | avg | 74ms | 79ms | 5ms | 6.73
| UserStore.AutocompleteUsersInChannel | avg | 133ms | 137ms | 4ms | 3.01
### Store times p99 (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| JobStore.GetNewestJobByStatusesAndType | p99 | 5ms | 26ms | 21ms | 424.24
| EmojiStore.GetMultipleByName | p99 | 5ms | 24ms | 19ms | 383.84
| ScheduledPostStore.GetPendingScheduledPosts | p99 | 5ms | 22ms | 17ms | 343.43
| ChannelStore.GetSidebarCategory | p99 | 5ms | 20ms | 15ms | 303.03
| ChannelStore.GetFileCount | p99 | 7ms | 28ms | 21ms | 289.75
| ThreadStore.Get | p99 | 5ms | 17ms | 12ms | 242.42
| ClusterDiscoveryStore.SetLastPingAt | p99 | 9ms | 24ms | 15ms | 164.59
| PluginStore.List | p99 | 8ms | 20ms | 12ms | 146.33
| JobStore.UpdateStatusOptimistically | p99 | 10ms | 23ms | 13ms | 130.65
| DraftStore.GetDraftsForUser | p99 | 11ms | 23ms | 12ms | 108.00
| FileInfoStore.GetByIds | p99 | 8ms | 15ms | 7ms | 85.37
| EmojiStore.GetByName | p99 | 6ms | 11ms | 5ms | 82.79
| SessionStore.Remove | p99 | 5ms | 9ms | 4ms | 80.81
| ChannelStore.Save | p99 | 48ms | 82ms | 34ms | 71.52
| GroupStore.AdminRoleGroupsForSyncableMember | p99 | 32ms | 55ms | 23ms | 71.21
| JobStore.GetCountByStatusAndType | p99 | 5ms | 8ms | 3ms | 60.61
| JobStore.GetAllByStatus | p99 | 12ms | 19ms | 7ms | 59.41
| FileInfoStore.SetContent | p99 | 22ms | 35ms | 13ms | 59.33
| SharedChannelStore.HasChannel | p99 | 5ms | 8ms | 3ms | 59.16
| ThreadStore.GetThreadForUser | p99 | 10ms | 15ms | 5ms | 50.39
| SessionStore.GetLRUSessions | p99 | 50ms | 72ms | 22ms | 44.31
| PreferenceStore.GetAll | p99 | 55ms | 79ms | 24ms | 43.45
| UserTermsOfServiceStore.GetByUser | p99 | 46ms | 66ms | 20ms | 43.23
| PropertyFieldStore.SearchPropertyFields | p99 | 42ms | 60ms | 18ms | 42.75
| ChannelBookmarkStore.GetBookmarksForChannelSince | p99 | 7ms | 10ms | 3ms | 42.08
| ChannelStore.GetChannelsWithUnreadsAndWithMentions | p99 | 7ms | 10ms | 3ms | 41.82
| GroupStore.GetByName | p99 | 58ms | 82ms | 24ms | 41.49
| SessionStore.Get | p99 | 58ms | 82ms | 24ms | 41.03
| PostAcknowledgementStore.GetForPosts | p99 | 10ms | 14ms | 4ms | 40.35
| PostPersistentNotificationStore.GetSingle | p99 | 5ms | 7ms | 2ms | 40.08
| ChannelStore.GetChannels | p99 | 21ms | 29ms | 8ms | 38.25
| ChannelStore.Get | p99 | 36ms | 49ms | 13ms | 36.29
| TeamStore.GetChannelUnreadsForAllTeams | p99 | 43ms | 58ms | 15ms | 34.95
| StatusStore.Get | p99 | 37ms | 50ms | 13ms | 34.94
| UserStore.GetForLogin | p99 | 61ms | 81ms | 20ms | 33.00
| ChannelStore.GetMembersForUserWithPagination | p99 | 43ms | 57ms | 14ms | 32.42
| TeamStore.GetMember | p99 | 22ms | 29ms | 7ms | 31.20
| GroupStore.GetGroups | p99 | 23ms | 30ms | 7ms | 30.74
| PostPriorityStore.GetForPosts | p99 | 13ms | 17ms | 4ms | 30.11
| ChannelStore.GetMemberLastViewedAt | p99 | 37ms | 48ms | 11ms | 29.90
| TeamStore.GetTeamsByUserId | p99 | 44ms | 57ms | 13ms | 29.70
| ChannelStore.GetByName | p99 | 54ms | 69ms | 15ms | 27.74
| ThreadStore.GetThreadsForUser | p99 | 11ms | 14ms | 3ms | 26.97
| TeamStore.GetAllPage | p99 | 45ms | 57ms | 12ms | 26.41
| PreferenceStore.Get | p99 | 8ms | 10ms | 2ms | 25.53
| ThreadStore.GetThreadFollowers | p99 | 8ms | 10ms | 2ms | 25.46
| PostStore.Get | p99 | 12ms | 15ms | 3ms | 25.37
| UserStore.IsEmpty | p99 | 36ms | 45ms | 9ms | 25.29
| ThreadStore.GetTotalUnreadMentions | p99 | 32ms | 40ms | 8ms | 25.17
| TeamStore.GetTeamsForUser | p99 | 44ms | 55ms | 11ms | 24.96
| ChannelStore.GetChannelsByUser | p99 | 41ms | 51ms | 10ms | 24.20
| ThreadStore.GetTeamsUnreadForUser | p99 | 47ms | 57ms | 10ms | 21.17
| FileInfoStore.AttachToPost | p99 | 10ms | 12ms | 2ms | 20.02
| ThreadStore.GetTotalUnreadThreads | p99 | 37ms | 44ms | 7ms | 19.07
| ThreadStore.GetTotalThreads | p99 | 37ms | 44ms | 7ms | 18.98
| PostStore.GetEtag | p99 | 38ms | 45ms | 7ms | 18.49
| ChannelStore.GetGuestCount | p99 | 67ms | 79ms | 12ms | 17.94
| ThreadStore.GetTotalUnreadUrgentMentions | p99 | 39ms | 46ms | 7ms | 17.87
| SessionStore.Save | p99 | 68ms | 80ms | 12ms | 17.52
| PostStore.GetPosts | p99 | 46ms | 54ms | 8ms | 17.48
| UserStore.GetAllProfiles | p99 | 40ms | 47ms | 7ms | 17.35
| ScheduledPostStore.GetScheduledPostsForUser | p99 | 42ms | 49ms | 7ms | 16.55
| ChannelStore.GetMembersForUser | p99 | 22ms | 25ms | 3ms | 13.48
| UserStore.Get | p99 | 15ms | 17ms | 2ms | 12.91
| ChannelStore.GetPublicChannelsForTeam | p99 | 52ms | 58ms | 6ms | 11.53
| ChannelStore.GetMembersForUserWithCursorPagination | p99 | 21ms | 23ms | 2ms | 9.40
| ChannelStore.GetAllChannelMembersForUser | p99 | 23ms | 25ms | 2ms | 8.81
| ChannelStore.SaveMember | p99 | 224ms | 243ms | 19ms | 8.50
| UserStore.Count | p99 | 438ms | 460ms | 22ms | 5.02
| ProductNoticesStore.View | p99 | 144ms | 149ms | 5ms | 3.46
| UserStore.Save | p99 | 208ms | 215ms | 7ms | 3.36
| UserStore.GetAllProfilesInChannel | p99 | 1.927s | 1.972s | 45ms | 2.33
| TeamStore.SaveMember | p99 | 225ms | 230ms | 5ms | 2.22
### Store times avg (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| PluginStore.SetWithOptions | avg | 7ms | 0s | -7ms | -106.10
| ThreadStore.MarkAllAsReadByTeam | avg | 3ms | 0s | -3ms | -104.14
| PluginStore.Delete | avg | 3ms | 0s | -3ms | -101.77
| UserStore.GetProfileByGroupChannelIdsForUser | avg | 6ms | 2ms | -4ms | -64.78
| StatusStore.SaveOrUpdate | avg | 9ms | 4ms | -5ms | -52.98
| ChannelStore.GetSidebarCategoriesForTeamForUser | avg | 9ms | 7ms | -2ms | -21.77
| ChannelStore.CreateInitialSidebarCategories | avg | 23ms | 18ms | -5ms | -21.42
| ChannelStore.AutocompleteInTeamForSearch | avg | 260ms | 240ms | -20ms | -7.68
| ChannelStore.UpdateSidebarCategories | avg | 31ms | 29ms | -2ms | -6.39
| ChannelStore.Autocomplete | avg | 1.03s | 986ms | -44ms | -4.27
| TeamStore.GetActiveMemberCount | avg | 98ms | 96ms | -2ms | -2.05
| PostStore.AnalyticsPostCount | avg | 507ms | 501ms | -6ms | -1.18
### Store times p99 (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| PluginStore.Get | p99 | 5ms | 0s | -5ms | -101.01
| ThreadStore.MarkAllAsReadByTeam | p99 | 5ms | 0s | -5ms | -101.01
| ChannelStore.GetMembers | p99 | 5ms | 0s | -5ms | -101.01
| PluginStore.SetWithOptions | p99 | 35ms | 0s | -35ms | -100.42
| PluginStore.Delete | p99 | 18ms | 0s | -18ms | -99.46
| StatusStore.SaveOrUpdate | p99 | 198ms | 22ms | -176ms | -89.04
| PostPriorityStore.GetForPost | p99 | 36ms | 5ms | -31ms | -86.72
| UserStore.GetByUsername | p99 | 27ms | 5ms | -22ms | -82.21
| ThreadStore.MarkAllAsReadByChannels | p99 | 20ms | 5ms | -15ms | -74.25
| PostAcknowledgementStore.GetForPost | p99 | 20ms | 5ms | -15ms | -73.93
| JobStore.Save | p99 | 18ms | 5ms | -13ms | -72.42
| PostStore.SetPostReminder | p99 | 24ms | 10ms | -14ms | -58.09
| PostStore.GetPostReminders | p99 | 22ms | 10ms | -12ms | -53.45
| UserStore.GetProfileByGroupChannelIdsForUser | p99 | 10ms | 5ms | -5ms | -50.25
| ChannelStore.CreateDirectChannel | p99 | 51ms | 29ms | -22ms | -43.12
| JobStore.UpdateOptimistically | p99 | 8ms | 5ms | -3ms | -39.22
| JobStore.UpdateStatus | p99 | 8ms | 5ms | -3ms | -39.22
| FileInfoStore.Save | p99 | 17ms | 11ms | -6ms | -36.30
| ChannelStore.Autocomplete | p99 | 3.413s | 2.49s | -923ms | -27.05
| ChannelStore.SearchGroupChannels | p99 | 13ms | 10ms | -3ms | -22.30
| ChannelStore.GetMemberCount | p99 | 644ms | 503ms | -141ms | -21.89
| ChannelStore.CreateInitialSidebarCategories | p99 | 99ms | 80ms | -19ms | -19.17
| ChannelStore.GetSidebarCategoriesForTeamForUser | p99 | 113ms | 95ms | -18ms | -15.92
| PreferenceStore.Save | p99 | 63ms | 53ms | -10ms | -15.78
| ChannelStore.GetAllChannelMembersNotifyPropsForChannel | p99 | 86ms | 75ms | -11ms | -12.81
| PropertyValueStore.SearchPropertyValues | p99 | 16ms | 14ms | -2ms | -12.38
| UserStore.UpdateFailedPasswordAttempts | p99 | 33ms | 29ms | -4ms | -12.25
| PostStore.SearchPostsForUser | p99 | 395ms | 377ms | -18ms | -4.56
| ChannelStore.AutocompleteInTeamForSearch | p99 | 2.38s | 2.356s | -24ms | -1.01
### API times avg (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| getChannel | avg | 3ms | 5ms | 2ms | 60.53
| followThreadByUser | avg | 10ms | 14ms | 4ms | 40.88
| getPostsForChannelAroundLastUnread | avg | 21ms | 24ms | 3ms | 14.07
| removeUserCustomStatus | avg | 87ms | 97ms | 10ms | 11.43
| createUser | avg | 323ms | 342ms | 19ms | 5.89
| addTeamMember | avg | 884ms | 934ms | 50ms | 5.65
| createGroupChannel | avg | 207ms | 216ms | 9ms | 4.34
| addChannelMember | avg | 140ms | 145ms | 5ms | 3.57
| searchUsers | avg | 58ms | 60ms | 2ms | 3.43
| login | avg | 70ms | 72ms | 2ms | 2.87
| createPost | avg | 148ms | 152ms | 4ms | 2.71
### API times p99 (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| getChannel | p99 | 11ms | 58ms | 47ms | 413.87
| saveReaction | p99 | 24ms | 55ms | 31ms | 129.77
| getDrafts | p99 | 11ms | 24ms | 13ms | 116.48
| followThreadByUser | p99 | 25ms | 48ms | 23ms | 93.40
| deletePost | p99 | 25ms | 48ms | 23ms | 92.56
| updateCategoriesForTeamForUser | p99 | 50ms | 92ms | 42ms | 84.42
| addChannelMember | p99 | 248ms | 425ms | 177ms | 71.29
| listChannelBookmarksForChannel | p99 | 9ms | 14ms | 5ms | 57.40
| listCPAFields | p99 | 45ms | 66ms | 21ms | 46.78
| getAllTeams | p99 | 47ms | 67ms | 20ms | 42.31
| getPreferences | p99 | 56ms | 79ms | 23ms | 41.29
| getChannelsForTeamForUser | p99 | 21ms | 29ms | 8ms | 38.06
| getTeamMembersForUser | p99 | 45ms | 61ms | 16ms | 35.25
| getFilePreview | p99 | 100ms | 134ms | 34ms | 34.16
| createGroupChannel | p99 | 487ms | 650ms | 163ms | 33.49
| getUser | p99 | 52ms | 69ms | 17ms | 32.69
| getTeamsForUser | p99 | 44ms | 58ms | 14ms | 31.98
| getChannelMembersForUser | p99 | 44ms | 57ms | 13ms | 29.59
| getThreadsForUser | p99 | 34ms | 43ms | 9ms | 26.62
| getChannelsForUser | p99 | 43ms | 53ms | 10ms | 23.43
| upsertDraft | p99 | 10ms | 12ms | 2ms | 20.04
| getTeamScheduledPosts | p99 | 80ms | 95ms | 15ms | 18.67
| getClientConfig | p99 | 49ms | 58ms | 9ms | 18.47
| getPostsForChannel | p99 | 96ms | 113ms | 17ms | 17.68
| viewChannel | p99 | 40ms | 47ms | 7ms | 17.42
| getTeamsUnreadForUser | p99 | 81ms | 95ms | 14ms | 17.29
| getPostsForChannelAroundLastUnread | p99 | 197ms | 231ms | 34ms | 17.22
| getChannelMember | p99 | 80ms | 92ms | 12ms | 15.01
| uploadFileStream | p99 | 1.457s | 1.672s | 215ms | 14.76
| getChannelMembersForTeamForUser | p99 | 22ms | 25ms | 3ms | 13.48
| updateReadStateThreadByUser | p99 | 25ms | 28ms | 3ms | 12.01
| getPublicChannelsForTeam | p99 | 52ms | 58ms | 6ms | 11.53
| login | p99 | 362ms | 399ms | 37ms | 10.21
| getUsers | p99 | 42ms | 46ms | 4ms | 9.45
| createPost | p99 | 895ms | 931ms | 36ms | 4.02
| addTeamMember | p99 | 3.941s | 4.075s | 134ms | 3.40
| getFileThumbnail | p99 | 96ms | 99ms | 3ms | 3.14
| getChannelStats | p99 | 223ms | 227ms | 4ms | 1.79
| createUser | p99 | 969ms | 982ms | 13ms | 1.34
| removeUserCustomStatus | p99 | 243ms | 246ms | 3ms | 1.23
### API times avg (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| getChannelMembers | avg | 2ms | 0s | -2ms | -128.46
| updateReadStateAllThreadsByUser | avg | 3ms | 0s | -3ms | -99.41
| getCategoriesForTeamForUser | avg | 10ms | 8ms | -2ms | -20.16
| deletePost | avg | 22ms | 20ms | -2ms | -9.30
| autocompleteChannelsForTeamForSearch | avg | 260ms | 240ms | -20ms | -7.68
| getProfileImage | avg | 99ms | 92ms | -7ms | -7.05
| createChannel | avg | 182ms | 173ms | -9ms | -4.93
| searchAllChannels | avg | 1.031s | 986ms | -45ms | -4.37
| createDirectChannel | avg | 143ms | 140ms | -3ms | -2.09
| getTeamStats | avg | 98ms | 96ms | -2ms | -2.04
| uploadFileStream | avg | 453ms | 448ms | -5ms | -1.10
### API times p99 (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| getChannelMembers | p99 | 5ms | 0s | -5ms | -101.01
| updateReadStateAllThreadsByUser | p99 | 5ms | 0s | -5ms | -101.01
| logout | p99 | 47ms | 25ms | -22ms | -47.30
| getTeamMember | p99 | 7ms | 5ms | -2ms | -29.30
| searchAllChannels | p99 | 3.413s | 2.49s | -923ms | -27.05
| getCategoriesForTeamForUser | p99 | 123ms | 98ms | -25ms | -20.25
| searchGroupChannels | p99 | 16ms | 13ms | -3ms | -19.03
| listCPAValues | p99 | 17ms | 14ms | -3ms | -17.23
| searchPostsInTeam | p99 | 416ms | 377ms | -39ms | -9.38
| autocompleteUsers | p99 | 446ms | 440ms | -6ms | -1.34
| autocompleteChannelsForTeamForSearch | p99 | 2.38s | 2.356s | -24ms | -1.01
### Store times:
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| AuditStore.Save |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 24ms| 24ms | 0s | 0.000
| BotStore.Get |  Avg| 1ms| 2ms | 1ms | 103.820
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelBookmarkStore.GetBookmarksForChannelSince |  Avg| 1ms| 2ms | 1ms | 71.260
| |  P99| 7ms| 10ms | 3ms | 42.081
| ChannelBookmarkStore.Save |  Avg| 12ms| 13ms | 1ms | 8.543
| |  P99| 25ms| 25ms | 0s | 0.000
| ChannelMemberHistoryStore.LogJoinEvent |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 23ms| 23ms | 0s | 0.000
| ChannelStore.Autocomplete |  Avg| 1.03s| 986ms | -44ms | -4.270
| |  P99| 3.413s| 2.49s | -923ms | -27.047
| ChannelStore.AutocompleteInTeamForSearch |  Avg| 260ms| 240ms | -20ms | -7.683
| |  P99| 2.38s| 2.356s | -24ms | -1.008
| ChannelStore.CreateDirectChannel |  Avg| 19ms| 19ms | 0s | 0.000
| |  P99| 51ms| 29ms | -22ms | -43.118
| ChannelStore.CreateInitialSidebarCategories |  Avg| 23ms| 18ms | -5ms | -21.424
| |  P99| 99ms| 80ms | -19ms | -19.172
| ChannelStore.Get |  Avg| 2ms| 3ms | 1ms | 44.961
| |  P99| 36ms| 49ms | 13ms | 36.291
| ChannelStore.GetAllChannelMembersForUser |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 23ms| 25ms | 2ms | 8.810
| ChannelStore.GetAllChannelMembersNotifyPropsForChannel |  Avg| 11ms| 13ms | 2ms | 17.714
| |  P99| 86ms| 75ms | -11ms | -12.810
| ChannelStore.GetByName |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 54ms| 69ms | 15ms | 27.741
| ChannelStore.GetChannelUnread |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelStore.GetChannels |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 21ms| 29ms | 8ms | 38.247
| ChannelStore.GetChannelsByUser |  Avg| 3ms| 4ms | 1ms | 31.939
| |  P99| 41ms| 51ms | 10ms | 24.199
| ChannelStore.GetChannelsWithUnreadsAndWithMentions |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 7ms| 10ms | 3ms | 41.818
| ChannelStore.GetFileCount |  Avg| 2ms| 3ms | 1ms | 45.386
| |  P99| 7ms| 28ms | 21ms | 289.749
| ChannelStore.GetGuestCount |  Avg| 4ms| 5ms | 1ms | 24.365
| |  P99| 67ms| 79ms | 12ms | 17.944
| ChannelStore.GetMember |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 22ms| 23ms | 1ms | 4.593
| ChannelStore.GetMemberCount |  Avg| 94ms| 95ms | 1ms | 1.062
| |  P99| 644ms| 503ms | -141ms | -21.887
| ChannelStore.GetMemberForPost |  Avg| 1ms| 2ms | 1ms | 71.012
| |  P99| 5ms| 6ms | 1ms | 20.045
| ChannelStore.GetMemberLastViewedAt |  Avg| 2ms| 3ms | 1ms | 42.357
| |  P99| 37ms| 48ms | 11ms | 29.904
| ChannelStore.GetMembers |  Avg| 1ms| 0s | -1ms | -78.711
| |  P99| 5ms| 0s | -5ms | -101.010
| ChannelStore.GetMembersForUser |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 22ms| 25ms | 3ms | 13.478
| ChannelStore.GetMembersForUserWithCursorPagination |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 21ms| 23ms | 2ms | 9.404
| ChannelStore.GetMembersForUserWithPagination |  Avg| 4ms| 5ms | 1ms | 26.565
| |  P99| 43ms| 57ms | 14ms | 32.417
| ChannelStore.GetPinnedPostCount |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelStore.GetPublicChannelsForTeam |  Avg| 9ms| 8ms | -1ms | -11.187
| |  P99| 52ms| 58ms | 6ms | 11.526
| ChannelStore.GetSidebarCategoriesForTeamForUser |  Avg| 9ms| 7ms | -2ms | -21.766
| |  P99| 113ms| 95ms | -18ms | -15.921
| ChannelStore.GetSidebarCategory |  Avg| 2ms| 3ms | 1ms | 43.070
| |  P99| 5ms| 20ms | 15ms | 303.030
| ChannelStore.GetTeamChannels |  Avg| 26ms| 27ms | 1ms | 3.808
| |  P99| 50ms| 50ms | 0s | 0.000
| ChannelStore.IncrementMentionCount |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 18ms| 17ms | -1ms | -5.639
| ChannelStore.IsReadOnlyChannel |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 6ms | 1ms | 20.022
| ChannelStore.Save |  Avg| 12ms| 14ms | 2ms | 16.151
| |  P99| 48ms| 82ms | 34ms | 71.517
| ChannelStore.SaveMember |  Avg| 32ms| 35ms | 3ms | 9.519
| |  P99| 224ms| 243ms | 19ms | 8.499
| ChannelStore.SearchGroupChannels |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 13ms| 10ms | -3ms | -22.302
| ChannelStore.UpdateLastViewedAt |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 15ms| 14ms | -1ms | -6.860
| ChannelStore.UpdateSidebarCategories |  Avg| 31ms| 29ms | -2ms | -6.395
| |  P99| 50ms| 50ms | 0s | 0.000
| ChannelStore.UpdateSidebarChannelsByPreferences |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ClusterDiscoveryStore.SetLastPingAt |  Avg| 4ms| 5ms | 1ms | 27.515
| |  P99| 9ms| 24ms | 15ms | 164.591
| CommandWebhookStore.Cleanup |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| DraftStore.Delete |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 9ms| 8ms | -1ms | -11.355
| DraftStore.DeleteDraftsAssociatedWithPost |  Avg| 7ms| 9ms | 2ms | 27.294
| |  P99| 24ms| 25ms | 1ms | 4.136
| DraftStore.Get |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| DraftStore.GetDraftsForUser |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 11ms| 23ms | 12ms | 108.004
| DraftStore.Upsert |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 9ms| 9ms | 0s | 0.000
| EmojiStore.GetByName |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 6ms| 11ms | 5ms | 82.791
| EmojiStore.GetMultipleByName |  Avg| 1ms| 4ms | 3ms | 350.642
| |  P99| 5ms| 24ms | 19ms | 383.838
| FileInfoStore.AttachToPost |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 10ms| 12ms | 2ms | 20.025
| FileInfoStore.Get |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| FileInfoStore.GetByIds |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 8ms| 15ms | 7ms | 85.371
| FileInfoStore.GetForPost |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| FileInfoStore.Save |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 17ms| 11ms | -6ms | -36.303
| FileInfoStore.SetContent |  Avg| 8ms| 9ms | 1ms | 12.385
| |  P99| 22ms| 35ms | 13ms | 59.335
| GroupStore.AdminRoleGroupsForSyncableMember |  Avg| 2ms| 3ms | 1ms | 44.130
| |  P99| 32ms| 55ms | 23ms | 71.207
| GroupStore.GetByName |  Avg| 4ms| 5ms | 1ms | 26.815
| |  P99| 58ms| 82ms | 24ms | 41.490
| GroupStore.GetGroups |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 23ms| 30ms | 7ms | 30.743
| JobStore.GetAllByStatus |  Avg| 1ms| 2ms | 1ms | 68.781
| |  P99| 12ms| 19ms | 7ms | 59.415
| JobStore.GetCountByStatusAndType |  Avg| 1ms| 2ms | 1ms | 121.596
| |  P99| 5ms| 8ms | 3ms | 60.606
| JobStore.GetNewestJobByStatusesAndType |  Avg| 1ms| 2ms | 1ms | 73.248
| |  P99| 5ms| 26ms | 21ms | 424.242
| JobStore.Save |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 18ms| 5ms | -13ms | -72.423
| JobStore.UpdateOptimistically |  Avg| 3ms| 4ms | 1ms | 30.079
| |  P99| 8ms| 5ms | -3ms | -39.216
| JobStore.UpdateStatus |  Avg| 3ms| 4ms | 1ms | 29.109
| |  P99| 8ms| 5ms | -3ms | -39.216
| JobStore.UpdateStatusOptimistically |  Avg| 7ms| 9ms | 2ms | 26.975
| |  P99| 10ms| 23ms | 13ms | 130.653
| LinkMetadataStore.Get |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| LinkMetadataStore.Save |  Avg| 4ms| 3ms | -1ms | -28.152
| |  P99| 8ms| 8ms | 0s | 0.000
| PluginStore.Delete |  Avg| 3ms| 0s | -3ms | -101.772
| |  P99| 18ms| 0s | -18ms | -99.456
| PluginStore.Get |  Avg| 1ms| 0s | -1ms | -103.014
| |  P99| 5ms| 0s | -5ms | -101.010
| PluginStore.List |  Avg| 1ms| 2ms | 1ms | 74.852
| |  P99| 8ms| 20ms | 12ms | 146.327
| PluginStore.SetWithOptions |  Avg| 7ms| 0s | -7ms | -106.102
| |  P99| 35ms| 0s | -35ms | -100.419
| PostAcknowledgementStore.GetForPost |  Avg| 2ms| 1ms | -1ms | -66.519
| |  P99| 20ms| 5ms | -15ms | -73.929
| PostAcknowledgementStore.GetForPosts |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 10ms| 14ms | 4ms | 40.346
| PostPersistentNotificationStore.DeleteExpired |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostPersistentNotificationStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostPersistentNotificationStore.GetSingle |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 7ms | 2ms | 40.084
| PostPriorityStore.GetForPost |  Avg| 2ms| 1ms | -1ms | -50.536
| |  P99| 36ms| 5ms | -31ms | -86.720
| PostPriorityStore.GetForPosts |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 13ms| 17ms | 4ms | 30.115
| PostStore.AnalyticsPostCount |  Avg| 507ms| 501ms | -6ms | -1.184
| |  P99| 995ms| 995ms | 0s | 0.000
| PostStore.Delete |  Avg| 15ms| 15ms | 0s | 0.000
| |  P99| 25ms| 25ms | 0s | 0.000
| PostStore.Get |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 12ms| 15ms | 3ms | 25.372
| PostStore.GetEtag |  Avg| 2ms| 3ms | 1ms | 42.735
| |  P99| 38ms| 45ms | 7ms | 18.493
| PostStore.GetMaxPostSize |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.GetPostIdAfterTime |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 20ms| 21ms | 1ms | 5.112
| PostStore.GetPostIdBeforeTime |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 8ms| 8ms | 0s | 0.000
| PostStore.GetPostReminderMetadata |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.GetPostReminders |  Avg| 7ms| 8ms | 1ms | 13.878
| |  P99| 22ms| 10ms | -12ms | -53.452
| PostStore.GetPosts |  Avg| 5ms| 6ms | 1ms | 19.476
| |  P99| 46ms| 54ms | 8ms | 17.479
| PostStore.GetPostsAfter |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.GetPostsBefore |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 13ms| 14ms | 1ms | 7.872
| PostStore.GetPostsByThread |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.GetPostsSince |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 44ms| 45ms | 1ms | 2.257
| PostStore.GetSingle |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.InvalidateLastPostTimeCache |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.Save |  Avg| 13ms| 14ms | 1ms | 7.434
| |  P99| 48ms| 49ms | 1ms | 2.065
| PostStore.SearchPostsForUser |  Avg| 46ms| 45ms | -1ms | -2.166
| |  P99| 395ms| 377ms | -18ms | -4.557
| PostStore.SetPostReminder |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 24ms| 10ms | -14ms | -58.090
| PostStore.Update |  Avg| 15ms| 15ms | 0s | 0.000
| |  P99| 26ms| 27ms | 1ms | 3.844
| PreferenceStore.DeleteCategoryAndName |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PreferenceStore.Get |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 8ms| 10ms | 2ms | 25.535
| PreferenceStore.GetAll |  Avg| 4ms| 5ms | 1ms | 23.293
| |  P99| 55ms| 79ms | 24ms | 43.455
| PreferenceStore.Save |  Avg| 12ms| 12ms | 0s | 0.000
| |  P99| 63ms| 53ms | -10ms | -15.782
| ProductNoticesStore.ClearOldNotices |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ProductNoticesStore.View |  Avg| 34ms| 34ms | 0s | 0.000
| |  P99| 144ms| 149ms | 5ms | 3.461
| PropertyFieldStore.SearchPropertyFields |  Avg| 3ms| 4ms | 1ms | 35.785
| |  P99| 42ms| 60ms | 18ms | 42.752
| PropertyValueStore.SearchPropertyValues |  Avg| 2ms| 1ms | -1ms | -64.889
| |  P99| 16ms| 14ms | -2ms | -12.383
| ReactionStore.GetForPost |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 12ms| 12ms | 0s | 0.000
| RoleStore.ChannelHigherScopedPermissions |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| RoleStore.GetByNames |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ScheduledPostStore.CreateScheduledPost |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ScheduledPostStore.GetMaxMessageSize |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ScheduledPostStore.GetPendingScheduledPosts |  Avg| 1ms| 3ms | 2ms | 219.854
| |  P99| 5ms| 22ms | 17ms | 343.434
| ScheduledPostStore.GetScheduledPostsForUser |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 42ms| 49ms | 7ms | 16.548
| ScheduledPostStore.UpdateOldScheduledPosts |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| SessionStore.Get |  Avg| 6ms| 8ms | 2ms | 30.800
| |  P99| 58ms| 82ms | 24ms | 41.034
| SessionStore.GetLRUSessions |  Avg| 3ms| 4ms | 1ms | 29.688
| |  P99| 50ms| 72ms | 22ms | 44.314
| SessionStore.GetSessionsExpired |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| SessionStore.GetSessionsWithActiveDeviceIds |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| SessionStore.Remove |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 5ms| 9ms | 4ms | 80.808
| SessionStore.Save |  Avg| 8ms| 9ms | 1ms | 12.574
| |  P99| 68ms| 80ms | 12ms | 17.525
| SessionStore.UpdateLastActivityAt |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 8ms| 8ms | 0s | 0.000
| SharedChannelStore.HasChannel |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 8ms | 3ms | 59.162
| StatusStore.Get |  Avg| 2ms| 3ms | 1ms | 42.146
| |  P99| 37ms| 50ms | 13ms | 34.945
| StatusStore.GetByIds |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| StatusStore.SaveOrUpdate |  Avg| 9ms| 4ms | -5ms | -52.981
| |  P99| 198ms| 22ms | -176ms | -89.038
| StatusStore.UpdateExpiredDNDStatuses |  Avg| 7ms| 8ms | 1ms | 14.937
| |  P99| 28ms| 28ms | 0s | 0.000
| StatusStore.UpdateLastActivityAt |  Avg| 3ms| 4ms | 1ms | 28.687
| |  P99| 8ms| 8ms | 0s | 0.000
| SystemStore.GetByName |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 21ms| 22ms | 1ms | 4.657
| TeamStore.Get |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 9ms| 10ms | 1ms | 11.646
| TeamStore.GetActiveMemberCount |  Avg| 98ms| 96ms | -2ms | -2.047
| |  P99| 100ms| 100ms | 0s | 0.000
| TeamStore.GetAllPage |  Avg| 3ms| 4ms | 1ms | 33.791
| |  P99| 45ms| 57ms | 12ms | 26.405
| TeamStore.GetChannelUnreadsForAllTeams |  Avg| 3ms| 4ms | 1ms | 33.981
| |  P99| 43ms| 58ms | 15ms | 34.947
| TeamStore.GetMember |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 22ms| 29ms | 7ms | 31.195
| TeamStore.GetTeamsByUserId |  Avg| 3ms| 4ms | 1ms | 32.893
| |  P99| 44ms| 57ms | 13ms | 29.701
| TeamStore.GetTeamsForUser |  Avg| 3ms| 4ms | 1ms | 33.673
| |  P99| 44ms| 55ms | 11ms | 24.962
| TeamStore.GetTotalMemberCount |  Avg| 74ms| 79ms | 5ms | 6.725
| |  P99| 100ms| 100ms | 0s | 0.000
| TeamStore.SaveMember |  Avg| 74ms| 75ms | 1ms | 1.348
| |  P99| 225ms| 230ms | 5ms | 2.218
| ThreadStore.Get |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 17ms | 12ms | 242.424
| ThreadStore.GetMembershipForUser |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 6ms | 1ms | 20.026
| ThreadStore.GetTeamsUnreadForUser |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 47ms| 57ms | 10ms | 21.167
| ThreadStore.GetThreadFollowers |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 8ms| 10ms | 2ms | 25.457
| ThreadStore.GetThreadForUser |  Avg| 2ms| 3ms | 1ms | 41.103
| |  P99| 10ms| 15ms | 5ms | 50.391
| ThreadStore.GetThreadUnreadReplyCount |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ThreadStore.GetThreadsForUser |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 11ms| 14ms | 3ms | 26.974
| ThreadStore.GetTotalThreads |  Avg| 2ms| 3ms | 1ms | 40.507
| |  P99| 37ms| 44ms | 7ms | 18.976
| ThreadStore.GetTotalUnreadMentions |  Avg| 2ms| 3ms | 1ms | 44.935
| |  P99| 32ms| 40ms | 8ms | 25.171
| ThreadStore.GetTotalUnreadThreads |  Avg| 2ms| 3ms | 1ms | 40.536
| |  P99| 37ms| 44ms | 7ms | 19.069
| ThreadStore.GetTotalUnreadUrgentMentions |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 39ms| 46ms | 7ms | 17.868
| ThreadStore.MaintainMembership |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 21ms| 21ms | 0s | 0.000
| ThreadStore.MarkAllAsReadByChannels |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 20ms| 5ms | -15ms | -74.253
| ThreadStore.MarkAllAsReadByTeam |  Avg| 3ms| 0s | -3ms | -104.138
| |  P99| 5ms| 0s | -5ms | -101.010
| ThreadStore.MarkAsRead |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 7ms| 8ms | 1ms | 13.441
| ThreadStore.UpdateMembership |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 8ms| 7ms | -1ms | -12.278
| TokenStore.Cleanup |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| UserAccessTokenStore.GetByToken |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| UserStore.AutocompleteUsersInChannel |  Avg| 133ms| 137ms | 4ms | 3.014
| |  P99| 463ms| 463ms | 0s | 0.000
| UserStore.Count |  Avg| 104ms| 113ms | 9ms | 8.663
| |  P99| 438ms| 460ms | 22ms | 5.022
| UserStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 15ms| 17ms | 2ms | 12.914
| UserStore.GetAllProfiles |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 40ms| 47ms | 7ms | 17.354
| UserStore.GetAllProfilesInChannel |  Avg| 264ms| 287ms | 23ms | 8.698
| |  P99| 1.927s| 1.972s | 45ms | 2.335
| UserStore.GetByUsername |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 27ms| 5ms | -22ms | -82.207
| UserStore.GetForLogin |  Avg| 4ms| 5ms | 1ms | 25.308
| |  P99| 61ms| 81ms | 20ms | 32.997
| UserStore.GetMany |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| UserStore.GetProfileByGroupChannelIdsForUser |  Avg| 6ms| 2ms | -4ms | -64.779
| |  P99| 10ms| 5ms | -5ms | -50.251
| UserStore.GetProfileByIds |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 19ms| 20ms | 1ms | 5.253
| UserStore.GetProfilesByUsernames |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| UserStore.GetProfilesInChannel |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| UserStore.GetProfilesNotInChannel |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| UserStore.GetUnreadCount |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 14ms| 13ms | -1ms | -7.072
| UserStore.IsEmpty |  Avg| 2ms| 3ms | 1ms | 47.929
| |  P99| 36ms| 45ms | 9ms | 25.289
| UserStore.Save |  Avg| 72ms| 71ms | -1ms | -1.396
| |  P99| 208ms| 215ms | 7ms | 3.363
| UserStore.Search |  Avg| 57ms| 58ms | 1ms | 1.740
| |  P99| 244ms| 244ms | 0s | 0.000
| UserStore.Update |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 10ms| 10ms | 0s | 0.000
| UserStore.UpdateFailedPasswordAttempts |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 33ms| 29ms | -4ms | -12.246
| UserStore.UpdateLastLogin |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 23ms| 22ms | -1ms | -4.289
| UserStore.UpdateUpdateAt |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 24ms| 24ms | 0s | 0.000
| UserTermsOfServiceStore.GetByUser |  Avg| 3ms| 4ms | 1ms | 33.866
| |  P99| 46ms| 66ms | 20ms | 43.226
| WebhookStore.GetOutgoingByTeam |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 20ms| 21ms | 1ms | 5.026
### API times:
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| addChannelMember | Avg| 140ms| 145ms | 5ms | 3.574
| | P99| 248ms| 425ms | 177ms | 71.286
| addTeamMember | Avg| 884ms| 934ms | 50ms | 5.655
| | P99| 3.941s| 4.075s | 134ms | 3.400
| autocompleteChannelsForTeamForSearch | Avg| 260ms| 240ms | -20ms | -7.681
| | P99| 2.38s| 2.356s | -24ms | -1.008
| autocompleteUsers | Avg| 114ms| 113ms | -1ms | -0.879
| | P99| 446ms| 440ms | -6ms | -1.344
| createChannel | Avg| 182ms| 173ms | -9ms | -4.932
| | P99| 249ms| 249ms | 0s | 0.000
| createChannelBookmark | Avg| 16ms| 16ms | 0s | 0.000
| | P99| 25ms| 25ms | 0s | 0.000
| createDirectChannel | Avg| 143ms| 140ms | -3ms | -2.091
| | P99| 248ms| 248ms | 0s | 0.000
| createGroupChannel | Avg| 207ms| 216ms | 9ms | 4.343
| | P99| 487ms| 650ms | 163ms | 33.487
| createPost | Avg| 148ms| 152ms | 4ms | 2.712
| | P99| 895ms| 931ms | 36ms | 4.023
| createSchedulePost | Avg| 4ms| 4ms | 0s | 0.000
| | P99| 9ms| 10ms | 1ms | 11.039
| createUser | Avg| 323ms| 342ms | 19ms | 5.888
| | P99| 969ms| 982ms | 13ms | 1.342
| deleteDraft | Avg| 1ms| 1ms | 0s | 0.000
| | P99| 8ms| 8ms | 0s | 0.000
| deletePost | Avg| 22ms| 20ms | -2ms | -9.301
| | P99| 25ms| 48ms | 23ms | 92.555
| followThreadByUser | Avg| 10ms| 14ms | 4ms | 40.877
| | P99| 25ms| 48ms | 23ms | 93.400
| getAllTeams | Avg| 3ms| 4ms | 1ms | 29.009
| | P99| 47ms| 67ms | 20ms | 42.313
| getCategoriesForTeamForUser | Avg| 10ms| 8ms | -2ms | -20.157
| | P99| 123ms| 98ms | -25ms | -20.253
| getChannel | Avg| 3ms| 5ms | 2ms | 60.529
| | P99| 11ms| 58ms | 47ms | 413.874
| getChannelMember | Avg| 7ms| 8ms | 1ms | 13.894
| | P99| 80ms| 92ms | 12ms | 15.012
| getChannelMembers | Avg| 2ms| 0s | -2ms | -128.462
| | P99| 5ms| 0s | -5ms | -101.010
| getChannelMembersForTeamForUser | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 22ms| 25ms | 3ms | 13.479
| getChannelMembersForUser | Avg| 4ms| 5ms | 1ms | 25.811
| | P99| 44ms| 57ms | 13ms | 29.589
| getChannelStats | Avg| 8ms| 8ms | 0s | 0.000
| | P99| 223ms| 227ms | 4ms | 1.794
| getChannelUnread | Avg| 1ms| 1ms | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getChannelsForTeamForUser | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 21ms| 29ms | 8ms | 38.064
| getChannelsForUser | Avg| 3ms| 4ms | 1ms | 30.366
| | P99| 43ms| 53ms | 10ms | 23.425
| getClientConfig | Avg| 8ms| 8ms | 0s | 0.000
| | P99| 49ms| 58ms | 9ms | 18.465
| getClientLicense | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getDrafts | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 11ms| 24ms | 13ms | 116.480
| getFilePreview | Avg| 40ms| 41ms | 1ms | 2.487
| | P99| 100ms| 134ms | 34ms | 34.155
| getFileThumbnail | Avg| 34ms| 35ms | 1ms | 2.959
| | P99| 96ms| 99ms | 3ms | 3.137
| getPostThread | Avg| 6ms| 6ms | 0s | 0.000
| | P99| 21ms| 21ms | 0s | 0.000
| getPostsForChannel | Avg| 14ms| 15ms | 1ms | 7.037
| | P99| 96ms| 113ms | 17ms | 17.683
| getPostsForChannelAroundLastUnread | Avg| 21ms| 24ms | 3ms | 14.074
| | P99| 197ms| 231ms | 34ms | 17.223
| getPreferences | Avg| 4ms| 5ms | 1ms | 22.725
| | P99| 56ms| 79ms | 23ms | 41.288
| getProfileImage | Avg| 99ms| 92ms | -7ms | -7.051
| | P99| 474ms| 470ms | -4ms | -0.844
| getPublicChannelsForTeam | Avg| 10ms| 9ms | -1ms | -10.228
| | P99| 52ms| 58ms | 6ms | 11.526
| getRolesByNames | Avg| 0s| 1ms | 1ms | 1239.772
| | P99| 5ms| 5ms | 0s | 0.000
| getTeamMember | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 7ms| 5ms | -2ms | -29.303
| getTeamMembersForUser | Avg| 3ms| 4ms | 1ms | 29.746
| | P99| 45ms| 61ms | 16ms | 35.245
| getTeamScheduledPosts | Avg| 6ms| 7ms | 1ms | 17.510
| | P99| 80ms| 95ms | 15ms | 18.672
| getTeamStats | Avg| 98ms| 96ms | -2ms | -2.045
| | P99| 100ms| 100ms | 0s | 0.000
| getTeamsForUser | Avg| 3ms| 4ms | 1ms | 32.121
| | P99| 44ms| 58ms | 14ms | 31.982
| getTeamsUnreadForUser | Avg| 6ms| 7ms | 1ms | 17.502
| | P99| 81ms| 95ms | 14ms | 17.292
| getThreadsForUser | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 34ms| 43ms | 9ms | 26.623
| getUser | Avg| 4ms| 4ms | 0s | 0.000
| | P99| 52ms| 69ms | 17ms | 32.688
| getUserStatus | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getUserStatusesByIds | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getUsers | Avg| 4ms| 5ms | 1ms | 22.987
| | P99| 42ms| 46ms | 4ms | 9.455
| getUsersByIds | Avg| 1ms| 1ms | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getUsersByNames | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 5ms| 6ms | 1ms | 20.009
| getWebappPlugins | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| listCPAFields | Avg| 3ms| 4ms | 1ms | 32.236
| | P99| 45ms| 66ms | 21ms | 46.784
| listCPAValues | Avg| 2ms| 1ms | -1ms | -60.004
| | P99| 17ms| 14ms | -3ms | -17.226
| listChannelBookmarksForChannel | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 9ms| 14ms | 5ms | 57.398
| login | Avg| 70ms| 72ms | 2ms | 2.867
| | P99| 362ms| 399ms | 37ms | 10.215
| logout | Avg| 20ms| 20ms | 0s | 0.000
| | P99| 47ms| 25ms | -22ms | -47.303
| patchPost | Avg| 22ms| 22ms | 0s | 0.000
| | P99| 49ms| 49ms | 0s | 0.000
| removeUserCustomStatus | Avg| 87ms| 97ms | 10ms | 11.429
| | P99| 243ms| 246ms | 3ms | 1.232
| root | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| saveReaction | Avg| 5ms| 6ms | 1ms | 19.129
| | P99| 24ms| 55ms | 31ms | 129.768
| searchAllChannels | Avg| 1.031s| 986ms | -45ms | -4.366
| | P99| 3.413s| 2.49s | -923ms | -27.047
| searchGroupChannels | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 16ms| 13ms | -3ms | -19.033
| searchPostsInTeam | Avg| 50ms| 49ms | -1ms | -2.010
| | P99| 416ms| 377ms | -39ms | -9.375
| searchUsers | Avg| 58ms| 60ms | 2ms | 3.433
| | P99| 244ms| 245ms | 1ms | 0.410
| setPostReminder | Avg| 12ms| 12ms | 0s | 0.000
| | P99| 25ms| 25ms | 0s | 0.000
| submitPerformanceReport | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| unfollowThreadByUser | Avg| 10ms| 11ms | 1ms | 9.733
| | P99| 25ms| 25ms | 0s | 0.000
| updateCategoriesForTeamForUser | Avg| 37ms| 36ms | -1ms | -2.672
| | P99| 50ms| 92ms | 42ms | 84.422
| updatePreferences | Avg| 10ms| 10ms | 0s | 0.000
| | P99| 25ms| 25ms | 0s | 0.000
| updateReadStateAllThreadsByUser | Avg| 3ms| 0s | -3ms | -99.406
| | P99| 5ms| 0s | -5ms | -101.010
| updateReadStateThreadByUser | Avg| 17ms| 17ms | 0s | 0.000
| | P99| 25ms| 28ms | 3ms | 12.010
| updateUserCustomStatus | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| uploadFileStream | Avg| 453ms| 448ms | -5ms | -1.104
| | P99| 1.457s| 1.672s | 215ms | 14.756
| upsertDraft | Avg| 4ms| 4ms | 0s | 0.000
| | P99| 10ms| 12ms | 2ms | 20.041
| viewChannel | Avg| 11ms| 11ms | 0s | 0.000
| | P99| 40ms| 47ms | 7ms | 17.416
