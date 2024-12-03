### Store times avg (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| PreferenceStore.DeleteCategoryAndName | avg | 0s | 2ms | 2ms | 409.28
| PostStore.GetPostReminders | avg | 2ms | 4ms | 2ms | 113.59
| PostStore.AnalyticsPostCount | avg | 347ms | 538ms | 191ms | 54.97
| UserStore.GetAllProfilesInChannel | avg | 153ms | 160ms | 7ms | 4.56
### Store times p99 (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| PostStore.GetPostReminders | p99 | 5ms | 46ms | 41ms | 828.28
| JobStore.GetCountByStatusAndType | p99 | 5ms | 38ms | 33ms | 666.67
| PreferenceStore.DeleteCategoryAndName | p99 | 5ms | 23ms | 18ms | 363.64
| DraftStore.DeleteDraftsAssociatedWithPost | p99 | 5ms | 23ms | 18ms | 363.64
| BotStore.Get | p99 | 5ms | 22ms | 17ms | 343.43
| JobStore.Save | p99 | 5ms | 21ms | 16ms | 323.23
| JobStore.UpdateStatus | p99 | 5ms | 18ms | 13ms | 262.63
| ThreadStore.Get | p99 | 5ms | 17ms | 12ms | 242.42
| TeamStore.GetMember | p99 | 5ms | 14ms | 9ms | 180.87
| FileInfoStore.AttachToPost | p99 | 10ms | 24ms | 14ms | 140.56
| UserStore.GetProfilesNotInChannel | p99 | 5ms | 10ms | 5ms | 101.01
| UserStore.GetByUsername | p99 | 10ms | 20ms | 10ms | 100.00
| PostStore.AnalyticsPostCount | p99 | 498ms | 995ms | 497ms | 99.90
| FileInfoStore.Save | p99 | 9ms | 18ms | 9ms | 99.29
| PostStore.GetPostsAfter | p99 | 5ms | 9ms | 4ms | 80.81
| JobStore.Get | p99 | 5ms | 9ms | 4ms | 80.81
| PostStore.GetPostReminderMetadata | p99 | 5ms | 9ms | 4ms | 80.78
| ChannelStore.GetMember | p99 | 12ms | 20ms | 8ms | 69.29
| ReactionStore.GetForPost | p99 | 10ms | 14ms | 4ms | 42.06
| ThreadStore.GetThreadFollowers | p99 | 9ms | 12ms | 3ms | 32.21
| UserStore.Get | p99 | 7ms | 9ms | 2ms | 30.40
| ChannelStore.GetByName | p99 | 33ms | 43ms | 10ms | 30.26
| SystemStore.GetByName | p99 | 7ms | 9ms | 2ms | 28.12
| UserStore.GetAllProfiles | p99 | 14ms | 18ms | 4ms | 27.59
| FileInfoStore.GetForPost | p99 | 7ms | 9ms | 2ms | 27.33
| ChannelStore.IncrementMentionCount | p99 | 10ms | 12ms | 2ms | 20.31
| ChannelStore.GetMemberForPost | p99 | 16ms | 19ms | 3ms | 19.24
| ChannelStore.GetMemberLastViewedAt | p99 | 16ms | 19ms | 3ms | 18.83
| UserTermsOfServiceStore.GetByUser | p99 | 16ms | 19ms | 3ms | 18.50
| PreferenceStore.Get | p99 | 11ms | 13ms | 2ms | 18.26
| ChannelStore.GetSidebarCategoriesForTeamForUser | p99 | 66ms | 78ms | 12ms | 18.18
| TeamStore.GetAllPage | p99 | 17ms | 20ms | 3ms | 17.27
| TeamStore.GetChannelUnreadsForAllTeams | p99 | 17ms | 20ms | 3ms | 17.16
| DraftStore.GetDraftsForUser | p99 | 12ms | 14ms | 2ms | 16.13
| TeamStore.GetTeamsForUser | p99 | 19ms | 22ms | 3ms | 15.76
| ChannelStore.GetChannels | p99 | 13ms | 15ms | 2ms | 15.06
| WebhookStore.GetOutgoingByTeam | p99 | 31ms | 35ms | 4ms | 12.93
| PluginStore.SetWithOptions | p99 | 16ms | 18ms | 2ms | 12.19
| StatusStore.Get | p99 | 17ms | 19ms | 2ms | 12.07
| PostStore.Get | p99 | 18ms | 20ms | 2ms | 11.11
| TeamStore.GetTeamsByUserId | p99 | 19ms | 21ms | 2ms | 10.80
| TeamStore.SaveMember | p99 | 56ms | 62ms | 6ms | 10.76
| PostStore.GetPosts | p99 | 19ms | 21ms | 2ms | 10.47
| UserStore.UpdateFailedPasswordAttempts | p99 | 21ms | 23ms | 2ms | 9.59
| PreferenceStore.GetAll | p99 | 21ms | 23ms | 2ms | 9.57
| ChannelStore.GetGuestCount | p99 | 21ms | 23ms | 2ms | 9.50
| PreferenceStore.Save | p99 | 34ms | 37ms | 3ms | 8.90
| SessionStore.Save | p99 | 23ms | 25ms | 2ms | 8.87
| UserStore.Save | p99 | 192ms | 209ms | 17ms | 8.85
| ChannelStore.CreateDirectChannel | p99 | 39ms | 42ms | 3ms | 7.79
| ChannelStore.CreateInitialSidebarCategories | p99 | 81ms | 84ms | 3ms | 3.71
| UserStore.GetAllProfilesInChannel | p99 | 473ms | 480ms | 7ms | 1.48
### Store times avg (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| ChannelStore.GetMembers | avg | 3ms | 0s | -3ms | -102.63
| ChannelStore.CreateSidebarCategory | avg | 23ms | 0s | -23ms | -99.68
| ChannelStore.GetAllChannelMemberIdsByChannelId | avg | 10ms | 0s | -10ms | -99.02
| BotStore.Save | avg | 2ms | 0s | -2ms | -92.15
| ChannelStore.AutocompleteInTeamForSearch | avg | 48ms | 11ms | -37ms | -76.43
| UserAccessTokenStore.GetByToken | avg | 4ms | 2ms | -2ms | -53.53
| ChannelStore.GetTeamChannels | avg | 18ms | 9ms | -9ms | -51.13
| StatusStore.SaveOrUpdate | avg | 13ms | 7ms | -6ms | -47.99
| ChannelStore.GetAllChannelMembersForUser | avg | 5ms | 3ms | -2ms | -43.51
| RoleStore.GetByNames | avg | 5ms | 3ms | -2ms | -36.47
| ChannelStore.GetAllChannelMembersNotifyPropsForChannel | avg | 18ms | 13ms | -5ms | -28.43
| PostStore.SearchPostsForUser | avg | 149ms | 138ms | -11ms | -7.38
### Store times p99 (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| ChannelStore.GetMembers | p99 | 5ms | 0s | -5ms | -101.01
| RetentionPolicyStore.GetCount | p99 | 5ms | 0s | -5ms | -101.01
| RetentionPolicyStore.GetAll | p99 | 5ms | 0s | -5ms | -101.01
| BotStore.Save | p99 | 5ms | 0s | -5ms | -101.01
| ChannelStore.CreateSidebarCategory | p99 | 25ms | 0s | -25ms | -100.60
| ChannelStore.GetAllChannelMemberIdsByChannelId | p99 | 38ms | 0s | -38ms | -98.70
| ChannelStore.AutocompleteInTeamForSearch | p99 | 1.36s | 28ms | -1.332s | -97.94
| UserAccessTokenStore.GetByToken | p99 | 47ms | 5ms | -42ms | -89.36
| ChannelStore.GetTeamChannels | p99 | 96ms | 10ms | -86ms | -89.12
| PostPersistentNotificationStore.Get | p99 | 21ms | 5ms | -16ms | -77.48
| RoleStore.ChannelHigherScopedPermissions | p99 | 23ms | 8ms | -15ms | -65.65
| StatusStore.SaveOrUpdate | p99 | 215ms | 90ms | -125ms | -58.27
| ChannelStore.GetAllChannelMembersNotifyPropsForChannel | p99 | 188ms | 80ms | -108ms | -57.57
| ThreadStore.MarkAllAsReadByChannels | p99 | 9ms | 5ms | -4ms | -46.51
| ClusterDiscoveryStore.SetLastPingAt | p99 | 30ms | 16ms | -14ms | -45.90
| ChannelStore.UpdateSidebarCategories | p99 | 92ms | 50ms | -42ms | -45.65
| ChannelStore.GetChannelUnread | p99 | 9ms | 5ms | -4ms | -43.01
| ChannelStore.GetSidebarCategory | p99 | 42ms | 25ms | -17ms | -40.48
| UserStore.Update | p99 | 15ms | 9ms | -6ms | -39.69
| ChannelStore.GetPinnedPostCount | p99 | 7ms | 5ms | -2ms | -28.48
| ThreadStore.MarkAsRead | p99 | 7ms | 5ms | -2ms | -28.05
| PostAcknowledgementStore.GetForPost | p99 | 26ms | 20ms | -6ms | -23.19
| FileInfoStore.SetContent | p99 | 22ms | 17ms | -5ms | -22.80
| FileInfoStore.GetByIds | p99 | 10ms | 8ms | -2ms | -21.01
| DraftStore.Delete | p99 | 10ms | 8ms | -2ms | -20.69
| ChannelStore.Save | p99 | 80ms | 66ms | -14ms | -17.45
| UserStore.GetUnreadCount | p99 | 19ms | 16ms | -3ms | -15.93
| GroupStore.AdminRoleGroupsForSyncableMember | p99 | 15ms | 13ms | -2ms | -13.35
| PostPriorityStore.GetForPost | p99 | 15ms | 13ms | -2ms | -13.03
| ChannelStore.GetAllChannelMembersForUser | p99 | 23ms | 20ms | -3ms | -12.83
| UserStore.AutocompleteUsersInChannel | p99 | 180ms | 159ms | -21ms | -11.65
### API times avg (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| viewChannel | avg | 8ms | 10ms | 2ms | 26.49
| removeUserCustomStatus | avg | 116ms | 136ms | 20ms | 17.29
| createGroupChannel | avg | 244ms | 268ms | 24ms | 9.85
| logout | avg | 22ms | 24ms | 2ms | 9.21
| addTeamMember | avg | 590ms | 614ms | 24ms | 4.07
| createUser | avg | 118ms | 122ms | 4ms | 3.39
### API times p99 (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| viewChannel | p99 | 25ms | 41ms | 16ms | 64.15
| getChannelsForUser | p99 | 5ms | 8ms | 3ms | 60.61
| getTeamMember | p99 | 8ms | 12ms | 4ms | 52.81
| upsertDraft | p99 | 10ms | 15ms | 5ms | 48.25
| createGroupChannel | p99 | 495ms | 685ms | 190ms | 38.35
| getChannelMember | p99 | 38ms | 49ms | 11ms | 29.28
| getClientConfig | p99 | 24ms | 30ms | 6ms | 25.30
| saveReaction | p99 | 30ms | 36ms | 6ms | 20.28
| getPublicChannelsForTeam | p99 | 40ms | 48ms | 8ms | 20.18
| getCategoriesForTeamForUser | p99 | 67ms | 79ms | 12ms | 17.87
| getTeamsForUser | p99 | 19ms | 22ms | 3ms | 16.13
| getDrafts | p99 | 12ms | 14ms | 2ms | 16.13
| getPreferences | p99 | 21ms | 24ms | 3ms | 14.07
| getPostsForChannelAroundLastUnread | p99 | 66ms | 75ms | 9ms | 13.67
| getChannelsForTeamForUser | p99 | 17ms | 19ms | 2ms | 11.57
| getAllTeams | p99 | 20ms | 22ms | 2ms | 10.22
| getUsers | p99 | 21ms | 23ms | 2ms | 9.32
| getTeamMembersForUser | p99 | 22ms | 24ms | 2ms | 9.11
| getUser | p99 | 23ms | 25ms | 2ms | 8.84
| getTeamsUnreadForUser | p99 | 23ms | 25ms | 2ms | 8.57
| getChannelStats | p99 | 31ms | 33ms | 2ms | 6.52
| updateReadStateThreadByUser | p99 | 84ms | 89ms | 5ms | 5.98
| createUser | p99 | 393ms | 411ms | 18ms | 4.58
| addTeamMember | p99 | 2.167s | 2.23s | 63ms | 2.91
### API times avg (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| createCategoryForTeamForUser | avg | 25ms | 0s | -25ms | -99.79
| patchPost | avg | 446ms | 20ms | -426ms | -95.45
| getChannelMembers | avg | 3ms | 0s | -3ms | -91.28
| autocompleteChannelsForTeamForSearch | avg | 48ms | 11ms | -37ms | -76.32
| createPost | avg | 238ms | 180ms | -58ms | -24.39
| createChannel | avg | 180ms | 140ms | -40ms | -22.20
| searchPostsInTeam | avg | 157ms | 145ms | -12ms | -7.65
| getProfileImage | avg | 81ms | 75ms | -6ms | -7.45
| uploadFileStream | avg | 421ms | 392ms | -29ms | -6.89
| createDirectChannel | avg | 179ms | 172ms | -7ms | -3.92
| addChannelMember | avg | 168ms | 166ms | -2ms | -1.19
### API times p99 (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| getChannelMembers | p99 | 5ms | 0s | -5ms | -101.01
| createCategoryForTeamForUser | p99 | 50ms | 0s | -50ms | -100.50
| autocompleteChannelsForTeamForSearch | p99 | 1.36s | 28ms | -1.332s | -97.94
| patchPost | p99 | 494ms | 46ms | -448ms | -90.73
| getChannel | p99 | 67ms | 10ms | -57ms | -84.76
| followThreadByUser | p99 | 25ms | 10ms | -15ms | -61.10
| updateCategoriesForTeamForUser | p99 | 226ms | 100ms | -126ms | -55.75
| setPostReminder | p99 | 92ms | 48ms | -44ms | -47.83
| getChannelUnread | p99 | 9ms | 5ms | -4ms | -43.01
| updatePreferences | p99 | 14ms | 9ms | -5ms | -35.92
| getPostThread | p99 | 36ms | 25ms | -11ms | -30.20
| removeUserCustomStatus | p99 | 335ms | 248ms | -87ms | -25.97
| unfollowThreadByUser | p99 | 23ms | 19ms | -4ms | -17.03
| autocompleteUsers | p99 | 163ms | 137ms | -26ms | -15.97
| createPost | p99 | 941ms | 842ms | -99ms | -10.53
| getProfileImage | p99 | 378ms | 352ms | -26ms | -6.88
| addChannelMember | p99 | 471ms | 460ms | -11ms | -2.34
| createDirectChannel | p99 | 484ms | 475ms | -9ms | -1.86
| getPostsForChannel | p99 | 185ms | 183ms | -2ms | -1.08
### Store times:
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| AuditStore.Save |  Avg| 2ms| 3ms | 1ms | 41.102
| |  P99| 20ms| 21ms | 1ms | 4.892
| BotStore.Get |  Avg| 2ms| 3ms | 1ms | 45.960
| |  P99| 5ms| 22ms | 17ms | 343.434
| BotStore.Save |  Avg| 2ms| 0s | -2ms | -92.155
| |  P99| 5ms| 0s | -5ms | -101.010
| ChannelBookmarkStore.GetBookmarksForChannelSince |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 9ms| 9ms | 0s | 0.000
| ChannelBookmarkStore.Save |  Avg| 5ms| 6ms | 1ms | 21.595
| |  P99| 10ms| 10ms | 0s | 0.000
| ChannelMemberHistoryStore.LogJoinEvent |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 12ms| 13ms | 1ms | 8.386
| ChannelStore.Autocomplete |  Avg| 33ms| 33ms | 0s | 0.000
| |  P99| 98ms| 98ms | 0s | 0.000
| ChannelStore.AutocompleteInTeamForSearch |  Avg| 48ms| 11ms | -37ms | -76.434
| |  P99| 1.36s| 28ms | -1.332s | -97.943
| ChannelStore.CreateDirectChannel |  Avg| 14ms| 14ms | 0s | 0.000
| |  P99| 39ms| 42ms | 3ms | 7.792
| ChannelStore.CreateInitialSidebarCategories |  Avg| 26ms| 26ms | 0s | 0.000
| |  P99| 81ms| 84ms | 3ms | 3.709
| ChannelStore.CreateSidebarCategory |  Avg| 23ms| 0s | -23ms | -99.680
| |  P99| 25ms| 0s | -25ms | -100.604
| ChannelStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 16ms| 16ms | 0s | 0.000
| ChannelStore.GetAllChannelMemberIdsByChannelId |  Avg| 10ms| 0s | -10ms | -99.016
| |  P99| 38ms| 0s | -38ms | -98.703
| ChannelStore.GetAllChannelMembersForUser |  Avg| 5ms| 3ms | -2ms | -43.512
| |  P99| 23ms| 20ms | -3ms | -12.831
| ChannelStore.GetAllChannelMembersNotifyPropsForChannel |  Avg| 18ms| 13ms | -5ms | -28.431
| |  P99| 188ms| 80ms | -108ms | -57.570
| ChannelStore.GetByName |  Avg| 4ms| 5ms | 1ms | 24.152
| |  P99| 33ms| 43ms | 10ms | 30.256
| ChannelStore.GetChannelUnread |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 9ms| 5ms | -4ms | -43.011
| ChannelStore.GetChannels |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 13ms| 15ms | 2ms | 15.058
| ChannelStore.GetChannelsByUser |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelStore.GetChannelsWithUnreadsAndWithMentions |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 9ms| 9ms | 0s | 0.000
| ChannelStore.GetFileCount |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 10ms| 11ms | 1ms | 10.291
| ChannelStore.GetGuestCount |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 21ms| 23ms | 2ms | 9.500
| ChannelStore.GetMember |  Avg| 1ms| 2ms | 1ms | 72.093
| |  P99| 12ms| 20ms | 8ms | 69.294
| ChannelStore.GetMemberCount |  Avg| 16ms| 16ms | 0s | 0.000
| |  P99| 48ms| 49ms | 1ms | 2.096
| ChannelStore.GetMemberForPost |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 16ms| 19ms | 3ms | 19.236
| ChannelStore.GetMemberLastViewedAt |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 16ms| 19ms | 3ms | 18.833
| ChannelStore.GetMembers |  Avg| 3ms| 0s | -3ms | -102.629
| |  P99| 5ms| 0s | -5ms | -101.010
| ChannelStore.GetMembersForUser |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 15ms| 16ms | 1ms | 6.666
| ChannelStore.GetPinnedPostCount |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 7ms| 5ms | -2ms | -28.484
| ChannelStore.GetPublicChannelsForTeam |  Avg| 13ms| 14ms | 1ms | 7.551
| |  P99| 40ms| 40ms | 0s | 0.000
| ChannelStore.GetSidebarCategoriesForTeamForUser |  Avg| 25ms| 25ms | 0s | 0.000
| |  P99| 66ms| 78ms | 12ms | 18.181
| ChannelStore.GetSidebarCategory |  Avg| 12ms| 12ms | 0s | 0.000
| |  P99| 42ms| 25ms | -17ms | -40.476
| ChannelStore.GetTeamChannels |  Avg| 18ms| 9ms | -9ms | -51.129
| |  P99| 96ms| 10ms | -86ms | -89.119
| ChannelStore.IncrementMentionCount |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 10ms| 12ms | 2ms | 20.313
| ChannelStore.Save |  Avg| 8ms| 8ms | 0s | 0.000
| |  P99| 80ms| 66ms | -14ms | -17.446
| ChannelStore.SaveMember |  Avg| 23ms| 23ms | 0s | 0.000
| |  P99| 87ms| 88ms | 1ms | 1.149
| ChannelStore.SearchGroupChannels |  Avg| 10ms| 10ms | 0s | 0.000
| |  P99| 25ms| 25ms | 0s | 0.000
| ChannelStore.UpdateLastViewedAt |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 9ms| 9ms | 0s | 0.000
| ChannelStore.UpdateSidebarCategories |  Avg| 43ms| 42ms | -1ms | -2.303
| |  P99| 92ms| 50ms | -42ms | -45.652
| ChannelStore.UpdateSidebarChannelsByPreferences |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ClusterDiscoveryStore.SetLastPingAt |  Avg| 3ms| 2ms | -1ms | -36.929
| |  P99| 30ms| 16ms | -14ms | -45.904
| CommandWebhookStore.Cleanup |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| DraftStore.Delete |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 10ms| 8ms | -2ms | -20.690
| DraftStore.DeleteDraftsAssociatedWithPost |  Avg| 2ms| 3ms | 1ms | 42.424
| |  P99| 5ms| 23ms | 18ms | 363.636
| DraftStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 8ms| 9ms | 1ms | 12.309
| DraftStore.GetDraftsForUser |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 12ms| 14ms | 2ms | 16.129
| DraftStore.Upsert |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 9ms| 10ms | 1ms | 10.789
| EmojiStore.GetByName |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 8ms| 8ms | 0s | 0.000
| EmojiStore.GetMultipleByName |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| FileInfoStore.AttachToPost |  Avg| 3ms| 4ms | 1ms | 28.737
| |  P99| 10ms| 24ms | 14ms | 140.562
| FileInfoStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 7ms| 8ms | 1ms | 13.831
| FileInfoStore.GetByIds |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 10ms| 8ms | -2ms | -21.009
| FileInfoStore.GetForPost |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 7ms| 9ms | 2ms | 27.328
| FileInfoStore.Save |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 9ms| 18ms | 9ms | 99.294
| FileInfoStore.SetContent |  Avg| 5ms| 4ms | -1ms | -22.042
| |  P99| 22ms| 17ms | -5ms | -22.804
| GroupStore.AdminRoleGroupsForSyncableMember |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 15ms| 13ms | -2ms | -13.349
| GroupStore.GetByName |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 20ms| 20ms | 0s | 0.000
| GroupStore.GetGroups |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 14ms| 15ms | 1ms | 7.376
| JobStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 9ms | 4ms | 80.808
| JobStore.GetAllByStatus |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 22ms| 23ms | 1ms | 4.605
| JobStore.GetCountByStatusAndType |  Avg| 2ms| 3ms | 1ms | 56.688
| |  P99| 5ms| 38ms | 33ms | 666.667
| JobStore.GetNewestJobByStatusesAndType |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 10ms| 10ms | 0s | 0.000
| JobStore.Save |  Avg| 2ms| 3ms | 1ms | 45.116
| |  P99| 5ms| 21ms | 16ms | 323.232
| JobStore.UpdateOptimistically |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| JobStore.UpdateStatus |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 18ms | 13ms | 262.626
| JobStore.UpdateStatusOptimistically |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 9ms| 9ms | 0s | 0.000
| LinkMetadataStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 8ms| 8ms | 0s | 0.000
| LinkMetadataStore.Save |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PluginStore.Delete |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 6ms| 7ms | 1ms | 16.520
| PluginStore.List |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PluginStore.SetWithOptions |  Avg| 2ms| 3ms | 1ms | 40.004
| |  P99| 16ms| 18ms | 2ms | 12.192
| PostAcknowledgementStore.GetForPost |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 26ms| 20ms | -6ms | -23.189
| PostAcknowledgementStore.GetForPosts |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 15ms| 15ms | 0s | 0.000
| PostPersistentNotificationStore.DeleteExpired |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostPersistentNotificationStore.Get |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 21ms| 5ms | -16ms | -77.482
| PostPersistentNotificationStore.GetSingle |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 7ms| 8ms | 1ms | 14.038
| PostPriorityStore.GetForPost |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 15ms| 13ms | -2ms | -13.030
| PostPriorityStore.GetForPosts |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 16ms| 17ms | 1ms | 6.090
| PostStore.AnalyticsPostCount |  Avg| 347ms| 538ms | 191ms | 54.972
| |  P99| 498ms| 995ms | 497ms | 99.899
| PostStore.Delete |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 10ms| 10ms | 0s | 0.000
| PostStore.Get |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 18ms| 20ms | 2ms | 11.107
| PostStore.GetEtag |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 18ms| 19ms | 1ms | 5.675
| PostStore.GetMaxPostSize |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.GetPostIdAfterTime |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 8ms| 9ms | 1ms | 12.441
| PostStore.GetPostIdBeforeTime |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.GetPostReminderMetadata |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 5ms| 9ms | 4ms | 80.783
| PostStore.GetPostReminders |  Avg| 2ms| 4ms | 2ms | 113.592
| |  P99| 5ms| 46ms | 41ms | 828.283
| PostStore.GetPosts |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 19ms| 21ms | 2ms | 10.466
| PostStore.GetPostsAfter |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 5ms| 9ms | 4ms | 80.808
| PostStore.GetPostsBefore |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 15ms| 16ms | 1ms | 6.544
| PostStore.GetPostsByThread |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 22ms| 22ms | 0s | 0.000
| PostStore.GetPostsSince |  Avg| 8ms| 8ms | 0s | 0.000
| |  P99| 46ms| 46ms | 0s | 0.000
| PostStore.GetSingle |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 7ms| 7ms | 0s | 0.000
| PostStore.InvalidateLastPostTimeCache |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.Save |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 24ms| 25ms | 1ms | 4.091
| PostStore.SearchPostsForUser |  Avg| 149ms| 138ms | -11ms | -7.381
| |  P99| 972ms| 970ms | -2ms | -0.206
| PostStore.SetPostReminder |  Avg| 3ms| 2ms | -1ms | -34.996
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.Update |  Avg| 9ms| 8ms | -1ms | -11.077
| |  P99| 25ms| 24ms | -1ms | -4.010
| PreferenceStore.DeleteCategoryAndName |  Avg| 0s| 2ms | 2ms | 409.281
| |  P99| 5ms| 23ms | 18ms | 363.636
| PreferenceStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 11ms| 13ms | 2ms | 18.257
| PreferenceStore.GetAll |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 21ms| 23ms | 2ms | 9.569
| PreferenceStore.Save |  Avg| 4ms| 5ms | 1ms | 22.785
| |  P99| 34ms| 37ms | 3ms | 8.901
| ProductNoticesStore.ClearOldNotices |  Avg| 12ms| 12ms | 0s | 0.000
| |  P99| 25ms| 25ms | 0s | 0.000
| ProductNoticesStore.View |  Avg| 14ms| 15ms | 1ms | 7.372
| |  P99| 94ms| 95ms | 1ms | 1.066
| ReactionStore.GetForPost |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 10ms| 14ms | 4ms | 42.065
| RetentionPolicyStore.GetAll |  Avg| 1ms| 0s | -1ms | -68.634
| |  P99| 5ms| 0s | -5ms | -101.010
| RetentionPolicyStore.GetCount |  Avg| 1ms| 0s | -1ms | -124.008
| |  P99| 5ms| 0s | -5ms | -101.010
| RoleStore.ChannelHigherScopedPermissions |  Avg| 4ms| 3ms | -1ms | -25.153
| |  P99| 23ms| 8ms | -15ms | -65.646
| RoleStore.GetByNames |  Avg| 5ms| 3ms | -2ms | -36.469
| |  P99| 24ms| 23ms | -1ms | -4.093
| SessionStore.Get |  Avg| 4ms| 3ms | -1ms | -27.711
| |  P99| 31ms| 32ms | 1ms | 3.278
| SessionStore.GetLRUSessions |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 17ms| 18ms | 1ms | 5.940
| SessionStore.GetSessionsExpired |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| SessionStore.GetSessionsWithActiveDeviceIds |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 9ms| 10ms | 1ms | 11.053
| SessionStore.Remove |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| SessionStore.Save |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 23ms| 25ms | 2ms | 8.865
| SessionStore.UpdateLastActivityAt |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 8ms| 9ms | 1ms | 11.841
| StatusStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 17ms| 19ms | 2ms | 12.075
| StatusStore.GetByIds |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 8ms| 9ms | 1ms | 12.384
| StatusStore.SaveOrUpdate |  Avg| 13ms| 7ms | -6ms | -47.993
| |  P99| 215ms| 90ms | -125ms | -58.266
| StatusStore.UpdateExpiredDNDStatuses |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| StatusStore.UpdateLastActivityAt |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 8ms| 8ms | 0s | 0.000
| SystemStore.GetByName |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 7ms| 9ms | 2ms | 28.116
| TeamStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 7ms| 8ms | 1ms | 13.956
| TeamStore.GetActiveMemberCount |  Avg| 35ms| 35ms | 0s | 0.000
| |  P99| 50ms| 50ms | 0s | 0.000
| TeamStore.GetAllPage |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 17ms| 20ms | 3ms | 17.269
| TeamStore.GetChannelUnreadsForAllTeams |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 17ms| 20ms | 3ms | 17.158
| TeamStore.GetMember |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 14ms | 9ms | 180.871
| TeamStore.GetTeamsByUserId |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 19ms| 21ms | 2ms | 10.802
| TeamStore.GetTeamsForUser |  Avg| 2ms| 3ms | 1ms | 42.146
| |  P99| 19ms| 22ms | 3ms | 15.764
| TeamStore.GetTotalMemberCount |  Avg| 32ms| 31ms | -1ms | -3.123
| |  P99| 50ms| 50ms | 0s | 0.000
| TeamStore.SaveMember |  Avg| 19ms| 20ms | 1ms | 5.260
| |  P99| 56ms| 62ms | 6ms | 10.759
| ThreadStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 17ms | 12ms | 242.424
| ThreadStore.GetMembershipForUser |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 9ms| 10ms | 1ms | 10.867
| ThreadStore.GetTeamsUnreadForUser |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 20ms| 20ms | 0s | 0.000
| ThreadStore.GetThreadFollowers |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 9ms| 12ms | 3ms | 32.213
| ThreadStore.GetThreadForUser |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 24ms| 24ms | 0s | 0.000
| ThreadStore.GetThreadUnreadReplyCount |  Avg| 5ms| 6ms | 1ms | 18.596
| |  P99| 24ms| 24ms | 0s | 0.000
| ThreadStore.GetThreadsForUser |  Avg| 3ms| 4ms | 1ms | 29.102
| |  P99| 16ms| 17ms | 1ms | 6.409
| ThreadStore.GetTotalThreads |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 17ms| 18ms | 1ms | 5.800
| ThreadStore.GetTotalUnreadMentions |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 19ms| 19ms | 0s | 0.000
| ThreadStore.GetTotalUnreadThreads |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 17ms| 18ms | 1ms | 5.975
| ThreadStore.GetTotalUnreadUrgentMentions |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 17ms| 18ms | 1ms | 5.771
| ThreadStore.MaintainMembership |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 10ms| 10ms | 0s | 0.000
| ThreadStore.MarkAllAsReadByChannels |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 9ms| 5ms | -4ms | -46.513
| ThreadStore.MarkAllAsReadByTeam |  Avg| 3ms| 2ms | -1ms | -33.186
| |  P99| 5ms| 5ms | 0s | 0.000
| ThreadStore.MarkAsRead |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 7ms| 5ms | -2ms | -28.050
| ThreadStore.UpdateMembership |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 6ms| 6ms | 0s | 0.000
| TokenStore.Cleanup |  Avg| 1ms| 0s | -1ms | -164.595
| |  P99| 5ms| 5ms | 0s | 0.000
| UserAccessTokenStore.GetByToken |  Avg| 4ms| 2ms | -2ms | -53.527
| |  P99| 47ms| 5ms | -42ms | -89.362
| UserStore.AutocompleteUsersInChannel |  Avg| 35ms| 35ms | 0s | 0.000
| |  P99| 180ms| 159ms | -21ms | -11.650
| UserStore.Count |  Avg| 10ms| 10ms | 0s | 0.000
| |  P99| 25ms| 25ms | 0s | 0.000
| UserStore.Get |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 7ms| 9ms | 2ms | 30.399
| UserStore.GetAllProfiles |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 14ms| 18ms | 4ms | 27.594
| UserStore.GetAllProfilesInChannel |  Avg| 153ms| 160ms | 7ms | 4.564
| |  P99| 473ms| 480ms | 7ms | 1.479
| UserStore.GetByUsername |  Avg| 2ms| 3ms | 1ms | 41.316
| |  P99| 10ms| 20ms | 10ms | 100.000
| UserStore.GetForLogin |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 19ms| 20ms | 1ms | 5.164
| UserStore.GetMany |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| UserStore.GetProfileByIds |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 10ms| 11ms | 1ms | 10.216
| UserStore.GetProfilesByUsernames |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 9ms| 10ms | 1ms | 10.615
| UserStore.GetProfilesInChannel |  Avg| 10ms| 10ms | 0s | 0.000
| |  P99| 25ms| 25ms | 0s | 0.000
| UserStore.GetProfilesNotInChannel |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 5ms| 10ms | 5ms | 101.010
| UserStore.GetUnreadCount |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 19ms| 16ms | -3ms | -15.932
| UserStore.IsEmpty |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 9ms| 9ms | 0s | 0.000
| UserStore.Save |  Avg| 72ms| 73ms | 1ms | 1.394
| |  P99| 192ms| 209ms | 17ms | 8.851
| UserStore.Search |  Avg| 27ms| 27ms | 0s | 0.000
| |  P99| 58ms| 58ms | 0s | 0.000
| UserStore.Update |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 15ms| 9ms | -6ms | -39.694
| UserStore.UpdateFailedPasswordAttempts |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 21ms| 23ms | 2ms | 9.587
| UserStore.UpdateLastLogin |  Avg| 3ms| 4ms | 1ms | 30.267
| |  P99| 17ms| 18ms | 1ms | 6.051
| UserStore.UpdateUpdateAt |  Avg| 3ms| 4ms | 1ms | 29.791
| |  P99| 18ms| 19ms | 1ms | 5.538
| UserTermsOfServiceStore.GetByUser |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 16ms| 19ms | 3ms | 18.503
| WebhookStore.GetOutgoingByTeam |  Avg| 5ms| 6ms | 1ms | 21.855
| |  P99| 31ms| 35ms | 4ms | 12.925
### API times:
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| addChannelMember | Avg| 168ms| 166ms | -2ms | -1.191
| | P99| 471ms| 460ms | -11ms | -2.337
| addTeamMember | Avg| 590ms| 614ms | 24ms | 4.068
| | P99| 2.167s| 2.23s | 63ms | 2.907
| autocompleteChannelsForTeamForSearch | Avg| 48ms| 11ms | -37ms | -76.317
| | P99| 1.36s| 28ms | -1.332s | -97.943
| autocompleteUsers | Avg| 33ms| 33ms | 0s | 0.000
| | P99| 163ms| 137ms | -26ms | -15.974
| createCategoryForTeamForUser | Avg| 25ms| 0s | -25ms | -99.790
| | P99| 50ms| 0s | -50ms | -100.503
| createChannel | Avg| 180ms| 140ms | -40ms | -22.199
| | P99| 249ms| 248ms | -1ms | -0.402
| createChannelBookmark | Avg| 11ms| 11ms | 0s | 0.000
| | P99| 25ms| 25ms | 0s | 0.000
| createDirectChannel | Avg| 179ms| 172ms | -7ms | -3.917
| | P99| 484ms| 475ms | -9ms | -1.861
| createGroupChannel | Avg| 244ms| 268ms | 24ms | 9.854
| | P99| 495ms| 685ms | 190ms | 38.353
| createPost | Avg| 238ms| 180ms | -58ms | -24.386
| | P99| 941ms| 842ms | -99ms | -10.526
| createUser | Avg| 118ms| 122ms | 4ms | 3.387
| | P99| 393ms| 411ms | 18ms | 4.579
| deleteDraft | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 9ms| 10ms | 1ms | 11.579
| deletePost | Avg| 12ms| 11ms | -1ms | -8.479
| | P99| 25ms| 25ms | 0s | 0.000
| followThreadByUser | Avg| 9ms| 8ms | -1ms | -10.924
| | P99| 25ms| 10ms | -15ms | -61.099
| getAllTeams | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 20ms| 22ms | 2ms | 10.222
| getCategoriesForTeamForUser | Avg| 25ms| 25ms | 0s | 0.000
| | P99| 67ms| 79ms | 12ms | 17.867
| getChannel | Avg| 5ms| 5ms | 0s | 0.000
| | P99| 67ms| 10ms | -57ms | -84.762
| getChannelMember | Avg| 5ms| 6ms | 1ms | 20.301
| | P99| 38ms| 49ms | 11ms | 29.283
| getChannelMembers | Avg| 3ms| 0s | -3ms | -91.282
| | P99| 5ms| 0s | -5ms | -101.010
| getChannelMembersForTeamForUser | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 17ms| 18ms | 1ms | 5.775
| getChannelStats | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 31ms| 33ms | 2ms | 6.519
| getChannelUnread | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 9ms| 5ms | -4ms | -43.011
| getChannelsForTeamForUser | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 17ms| 19ms | 2ms | 11.573
| getChannelsForUser | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 5ms| 8ms | 3ms | 60.606
| getClientConfig | Avg| 2ms| 3ms | 1ms | 40.913
| | P99| 24ms| 30ms | 6ms | 25.296
| getDrafts | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 12ms| 14ms | 2ms | 16.129
| getFilePreview | Avg| 37ms| 37ms | 0s | 0.000
| | P99| 94ms| 94ms | 0s | 0.000
| getFileThumbnail | Avg| 32ms| 31ms | -1ms | -3.119
| | P99| 86ms| 86ms | 0s | 0.000
| getPostThread | Avg| 10ms| 10ms | 0s | 0.000
| | P99| 36ms| 25ms | -11ms | -30.197
| getPostsForChannel | Avg| 20ms| 20ms | 0s | 0.000
| | P99| 185ms| 183ms | -2ms | -1.081
| getPostsForChannelAroundLastUnread | Avg| 14ms| 15ms | 1ms | 7.036
| | P99| 66ms| 75ms | 9ms | 13.668
| getPreferences | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 21ms| 24ms | 3ms | 14.072
| getProfileImage | Avg| 81ms| 75ms | -6ms | -7.448
| | P99| 378ms| 352ms | -26ms | -6.881
| getPublicChannelsForTeam | Avg| 14ms| 15ms | 1ms | 6.980
| | P99| 40ms| 48ms | 8ms | 20.185
| getTeamMember | Avg| 1ms| 1ms | 0s | 0.000
| | P99| 8ms| 12ms | 4ms | 52.806
| getTeamMembersForUser | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 22ms| 24ms | 2ms | 9.111
| getTeamStats | Avg| 36ms| 36ms | 0s | 0.000
| | P99| 50ms| 50ms | 0s | 0.000
| getTeamsForUser | Avg| 2ms| 3ms | 1ms | 42.069
| | P99| 19ms| 22ms | 3ms | 16.130
| getTeamsUnreadForUser | Avg| 4ms| 4ms | 0s | 0.000
| | P99| 23ms| 25ms | 2ms | 8.568
| getThreadsForUser | Avg| 3ms| 4ms | 1ms | 28.820
| | P99| 19ms| 20ms | 1ms | 5.322
| getUser | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 23ms| 25ms | 2ms | 8.841
| getUserStatus | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getUserStatusesByIds | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getUsers | Avg| 3ms| 4ms | 1ms | 29.348
| | P99| 21ms| 23ms | 2ms | 9.320
| getUsersByIds | Avg| 1ms| 1ms | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getUsersByNames | Avg| 2ms| 3ms | 1ms | 40.008
| | P99| 10ms| 10ms | 0s | 0.000
| getWebappPlugins | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| listChannelBookmarksForChannel | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 10ms| 10ms | 0s | 0.000
| login | Avg| 54ms| 55ms | 1ms | 1.859
| | P99| 241ms| 242ms | 1ms | 0.415
| logout | Avg| 22ms| 24ms | 2ms | 9.213
| | P99| 48ms| 49ms | 1ms | 2.067
| patchPost | Avg| 446ms| 20ms | -426ms | -95.448
| | P99| 494ms| 46ms | -448ms | -90.734
| removeUserCustomStatus | Avg| 116ms| 136ms | 20ms | 17.293
| | P99| 335ms| 248ms | -87ms | -25.969
| root | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| saveReaction | Avg| 9ms| 9ms | 0s | 0.000
| | P99| 30ms| 36ms | 6ms | 20.285
| searchAllChannels | Avg| 34ms| 34ms | 0s | 0.000
| | P99| 98ms| 98ms | 0s | 0.000
| searchGroupChannels | Avg| 10ms| 10ms | 0s | 0.000
| | P99| 25ms| 25ms | 0s | 0.000
| searchPostsInTeam | Avg| 157ms| 145ms | -12ms | -7.651
| | P99| 982ms| 976ms | -6ms | -0.611
| searchUsers | Avg| 28ms| 28ms | 0s | 0.000
| | P99| 62ms| 61ms | -1ms | -1.601
| setPostReminder | Avg| 16ms| 15ms | -1ms | -6.089
| | P99| 92ms| 48ms | -44ms | -47.826
| submitPerformanceReport | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| unfollowThreadByUser | Avg| 9ms| 8ms | -1ms | -11.726
| | P99| 23ms| 19ms | -4ms | -17.030
| updateCategoriesForTeamForUser | Avg| 69ms| 68ms | -1ms | -1.441
| | P99| 226ms| 100ms | -126ms | -55.752
| updatePreferences | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 14ms| 9ms | -5ms | -35.922
| updateReadStateAllThreadsByUser | Avg| 3ms| 2ms | -1ms | -31.215
| | P99| 5ms| 5ms | 0s | 0.000
| updateReadStateThreadByUser | Avg| 33ms| 34ms | 1ms | 3.007
| | P99| 84ms| 89ms | 5ms | 5.984
| updateUserCustomStatus | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| uploadFileStream | Avg| 421ms| 392ms | -29ms | -6.888
| | P99| 993ms| 987ms | -6ms | -0.605
| upsertDraft | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 10ms| 15ms | 5ms | 48.246
| viewChannel | Avg| 8ms| 10ms | 2ms | 26.491
| | P99| 25ms| 41ms | 16ms | 64.151
