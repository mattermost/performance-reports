### Store times avg (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| ChannelBookmarkStore.UpdateSortOrder | avg | 21ms | 231ms | 210ms | 979.57
| ThreadStore.MarkAllAsReadByTeam | avg | 7ms | 21ms | 14ms | 209.42
| JobStore.GetNewestJobByStatusesAndType | avg | 6ms | 13ms | 7ms | 118.45
| StatusStore.UpdateExpiredDNDStatuses | avg | 11ms | 21ms | 10ms | 90.99
| UserStore.Save | avg | 95ms | 175ms | 80ms | 83.97
| PostStore.Delete | avg | 37ms | 62ms | 25ms | 67.11
| DraftStore.DeleteDraftsAssociatedWithPost | avg | 22ms | 36ms | 14ms | 64.73
| UserStore.GetProfilesInChannel | avg | 10ms | 16ms | 6ms | 60.96
| JobStore.GetCountByStatusAndType | avg | 12ms | 19ms | 7ms | 60.67
| TeamStore.GetTotalMemberCount | avg | 47ms | 72ms | 25ms | 52.83
| RoleStore.GetByNames | avg | 28ms | 41ms | 13ms | 46.68
| SessionStore.Remove | avg | 7ms | 10ms | 3ms | 43.20
| TeamStore.GetActiveMemberCount | avg | 58ms | 79ms | 21ms | 36.19
| FileInfoStore.GetByIds | avg | 11ms | 15ms | 4ms | 35.93
| PreferenceStore.DeleteCategoryAndName | avg | 21ms | 28ms | 7ms | 33.66
| ScheduledPostStore.CreateScheduledPost | avg | 12ms | 16ms | 4ms | 33.17
| UserStore.GetMany | avg | 9ms | 12ms | 3ms | 32.27
| ChannelStore.GetTeamChannels | avg | 42ms | 55ms | 13ms | 30.80
| JobStore.UpdateStatus | avg | 10ms | 13ms | 3ms | 28.94
| JobStore.UpdateOptimistically | avg | 10ms | 13ms | 3ms | 28.74
| ChannelStore.GetMembers | avg | 15ms | 19ms | 4ms | 26.30
| FileInfoStore.AttachToPost | avg | 18ms | 22ms | 4ms | 22.19
| ChannelBookmarkStore.Get | avg | 9ms | 11ms | 2ms | 21.24
| ChannelStore.CreateDirectChannel | avg | 67ms | 81ms | 14ms | 20.75
| JobStore.Save | avg | 10ms | 12ms | 2ms | 20.45
| ThreadStore.MarkAllAsReadByChannels | avg | 10ms | 12ms | 2ms | 20.23
| PreferenceStore.Get | avg | 11ms | 13ms | 2ms | 18.11
| DraftStore.Delete | avg | 12ms | 14ms | 2ms | 16.42
| PropertyValueStore.SearchPropertyValues | avg | 13ms | 15ms | 2ms | 15.78
| PostStore.AnalyticsPostCount | avg | 542ms | 610ms | 68ms | 12.54
| PostStore.GetPostReminders | avg | 21ms | 23ms | 2ms | 9.57
| ChannelStore.GetAllChannelMembersNotifyPropsForChannel | avg | 22ms | 24ms | 2ms | 9.26
| ProductNoticesStore.View | avg | 92ms | 100ms | 8ms | 8.73
| ChannelStore.CreateInitialSidebarCategories | avg | 38ms | 41ms | 3ms | 7.83
| ChannelStore.GetPublicChannelsForTeam | avg | 29ms | 31ms | 2ms | 7.01
| ChannelStore.SaveMember | avg | 59ms | 63ms | 4ms | 6.79
| PreferenceStore.Save | avg | 30ms | 32ms | 2ms | 6.71
| ChannelStore.Save | avg | 50ms | 52ms | 2ms | 3.98
| ChannelStore.AutocompleteInTeamForSearch | avg | 66ms | 68ms | 2ms | 3.05
| UserStore.GetAllProfilesInChannel | avg | 354ms | 358ms | 4ms | 1.13
### Store times p99 (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| ChannelBookmarkStore.UpdateSortOrder | p99 | 96ms | 495ms | 399ms | 415.60
| ThreadStore.MarkAllAsReadByTeam | p99 | 23ms | 97ms | 74ms | 314.90
| JobStore.GetNewestJobByStatusesAndType | p99 | 54ms | 219ms | 165ms | 305.56
| ChannelStore.GetMembers | p99 | 25ms | 98ms | 73ms | 293.76
| PostStore.Delete | p99 | 232ms | 850ms | 618ms | 266.38
| ChannelBookmarkStore.Delete | p99 | 95ms | 233ms | 138ms | 145.26
| TeamStore.GetTotalMemberCount | p99 | 99ms | 240ms | 141ms | 142.37
| StatusStore.UpdateExpiredDNDStatuses | p99 | 93ms | 218ms | 125ms | 134.70
| PostStore.GetPostReminderMetadata | p99 | 82ms | 192ms | 110ms | 134.14
| TeamStore.GetActiveMemberCount | p99 | 212ms | 450ms | 238ms | 112.00
| ScheduledPostStore.CreateScheduledPost | p99 | 93ms | 182ms | 89ms | 96.14
| BotStore.Get | p99 | 24ms | 46ms | 22ms | 91.00
| ChannelBookmarkStore.Save | p99 | 235ms | 430ms | 195ms | 83.15
| ChannelStore.CreateDirectChannel | p99 | 466ms | 825ms | 359ms | 76.96
| UserStore.Save | p99 | 404ms | 678ms | 274ms | 67.85
| PostStore.GetPostsAfter | p99 | 98ms | 149ms | 51ms | 52.23
| ChannelStore.UpdateSidebarCategories | p99 | 540ms | 805ms | 265ms | 49.08
| ThreadStore.MarkAllAsReadByChannels | p99 | 97ms | 142ms | 45ms | 46.40
| PropertyFieldStore.SearchPropertyFields | p99 | 100ms | 136ms | 36ms | 36.09
| PostStore.GetSingle | p99 | 99ms | 126ms | 27ms | 27.15
| UserStore.GetForLogin | p99 | 100ms | 126ms | 26ms | 25.89
| EmojiStore.GetByName | p99 | 119ms | 149ms | 30ms | 25.15
| LinkMetadataStore.Get | p99 | 112ms | 137ms | 25ms | 22.36
| DraftStore.Delete | p99 | 126ms | 154ms | 28ms | 22.31
| ChannelStore.GetChannelsWithUnreadsAndWithMentions | p99 | 133ms | 162ms | 29ms | 21.80
| FileInfoStore.GetByIds | p99 | 179ms | 217ms | 38ms | 21.21
| ChannelStore.AutocompleteInTeamForSearch | p99 | 356ms | 427ms | 71ms | 19.94
| ThreadStore.GetTotalUnreadThreads | p99 | 100ms | 119ms | 19ms | 19.05
| PropertyValueStore.SearchPropertyValues | p99 | 166ms | 195ms | 29ms | 17.51
| GroupStore.GetGroups | p99 | 120ms | 140ms | 20ms | 16.67
| PreferenceStore.Save | p99 | 257ms | 296ms | 39ms | 15.17
| TeamStore.Get | p99 | 97ms | 111ms | 14ms | 14.44
| ThreadStore.GetTotalUnreadMentions | p99 | 108ms | 123ms | 15ms | 13.95
| TeamStore.GetTeamsForUser | p99 | 106ms | 120ms | 14ms | 13.23
| ChannelStore.GetSidebarCategory | p99 | 270ms | 305ms | 35ms | 12.96
| SessionStore.GetLRUSessions | p99 | 85ms | 96ms | 11ms | 12.91
| PreferenceStore.Get | p99 | 165ms | 186ms | 21ms | 12.75
| PostStore.GetPostReminders | p99 | 201ms | 226ms | 25ms | 12.47
| ChannelStore.GetMember | p99 | 116ms | 130ms | 14ms | 12.08
| UserStore.GetProfilesInChannel | p99 | 84ms | 94ms | 10ms | 11.90
| FileInfoStore.AttachToPost | p99 | 204ms | 228ms | 24ms | 11.75
| DraftStore.DeleteDraftsAssociatedWithPost | p99 | 214ms | 239ms | 25ms | 11.68
| UserStore.UpdateLastLogin | p99 | 78ms | 87ms | 9ms | 11.47
| ThreadStore.GetTotalUnreadUrgentMentions | p99 | 105ms | 117ms | 12ms | 11.42
| ChannelStore.GetGuestCount | p99 | 141ms | 157ms | 16ms | 11.37
| JobStore.GetCountByStatusAndType | p99 | 204ms | 227ms | 23ms | 11.27
| SessionStore.Save | p99 | 177ms | 197ms | 20ms | 11.27
| UserTermsOfServiceStore.GetByUser | p99 | 99ms | 110ms | 11ms | 11.09
| ClusterDiscoveryStore.SetLastPingAt | p99 | 199ms | 221ms | 22ms | 11.07
| UserStore.GetByUsername | p99 | 138ms | 153ms | 15ms | 10.85
| ThreadStore.GetTotalThreads | p99 | 103ms | 114ms | 11ms | 10.70
| PostStore.GetPostIdBeforeTime | p99 | 108ms | 119ms | 11ms | 10.18
| ChannelMemberHistoryStore.LogJoinEvent | p99 | 75ms | 82ms | 7ms | 9.36
| UserStore.Get | p99 | 152ms | 166ms | 14ms | 9.22
| UserStore.GetUnreadCount | p99 | 118ms | 128ms | 10ms | 8.44
| ChannelStore.GetMembersForUserWithPagination | p99 | 115ms | 124ms | 9ms | 7.84
| ProductNoticesStore.View | p99 | 800ms | 861ms | 61ms | 7.63
| WebhookStore.GetOutgoingByTeam | p99 | 191ms | 205ms | 14ms | 7.33
| ChannelStore.UpdateLastViewedAt | p99 | 97ms | 104ms | 7ms | 7.25
| JobStore.Save | p99 | 85ms | 91ms | 6ms | 7.06
| ChannelBookmarkStore.GetBookmarksForChannelSince | p99 | 143ms | 153ms | 10ms | 6.98
| SessionStore.GetSessionsWithActiveDeviceIds | p99 | 101ms | 108ms | 7ms | 6.95
| ChannelStore.CreateInitialSidebarCategories | p99 | 386ms | 411ms | 25ms | 6.48
| PostAcknowledgementStore.GetForPosts | p99 | 207ms | 220ms | 13ms | 6.27
| UserStore.UpdateUpdateAt | p99 | 80ms | 85ms | 5ms | 6.22
| PreferenceStore.DeleteCategoryAndName | p99 | 214ms | 227ms | 13ms | 6.07
| DraftStore.Upsert | p99 | 173ms | 183ms | 10ms | 5.79
| PostPriorityStore.GetForPosts | p99 | 212ms | 223ms | 11ms | 5.19
| PostStore.Update | p99 | 232ms | 244ms | 12ms | 5.17
| EmojiStore.GetMultipleByName | p99 | 224ms | 235ms | 11ms | 4.90
| UserStore.Update | p99 | 233ms | 244ms | 11ms | 4.71
| PostStore.GetPosts | p99 | 88ms | 92ms | 4ms | 4.57
| SessionStore.UpdateLastActivityAt | p99 | 93ms | 97ms | 4ms | 4.31
| ChannelStore.GetFileCount | p99 | 163ms | 170ms | 7ms | 4.29
| ChannelStore.SaveMember | p99 | 470ms | 490ms | 20ms | 4.25
| GroupStore.GetByName | p99 | 96ms | 100ms | 4ms | 4.16
| UserStore.AutocompleteUsersInChannel | p99 | 352ms | 366ms | 14ms | 3.98
| StatusStore.GetByIds | p99 | 207ms | 215ms | 8ms | 3.87
| FileInfoStore.Get | p99 | 182ms | 189ms | 7ms | 3.84
| ChannelStore.GetAllChannelMembersForUser | p99 | 168ms | 174ms | 6ms | 3.57
| ChannelStore.IncrementMentionCount | p99 | 115ms | 119ms | 4ms | 3.46
| ChannelStore.GetByName | p99 | 121ms | 125ms | 4ms | 3.32
| StatusStore.Get | p99 | 151ms | 156ms | 5ms | 3.31
| TeamStore.GetTeamsByUserId | p99 | 121ms | 125ms | 4ms | 3.30
| ThreadStore.UpdateMembership | p99 | 91ms | 94ms | 3ms | 3.30
| ScheduledPostStore.UpdateOldScheduledPosts | p99 | 92ms | 95ms | 3ms | 3.27
| ThreadStore.MarkAsRead | p99 | 92ms | 95ms | 3ms | 3.26
| ThreadStore.GetThreadForUser | p99 | 215ms | 222ms | 7ms | 3.25
| ChannelBookmarkStore.Get | p99 | 92ms | 95ms | 3ms | 3.24
| SessionStore.GetSessionsExpired | p99 | 94ms | 97ms | 3ms | 3.21
| StatusStore.SaveOrUpdate | p99 | 156ms | 161ms | 5ms | 3.20
| StatusStore.UpdateLastActivityAt | p99 | 94ms | 97ms | 3ms | 3.19
| UserStore.UpdateFailedPasswordAttempts | p99 | 96ms | 99ms | 3ms | 3.14
| PostPersistentNotificationStore.GetSingle | p99 | 96ms | 99ms | 3ms | 3.13
| RoleStore.GetByNames | p99 | 229ms | 236ms | 7ms | 3.05
| UserStore.Count | p99 | 181ms | 186ms | 5ms | 2.76
| ChannelStore.GetTeamChannels | p99 | 438ms | 450ms | 12ms | 2.74
| PostStore.GetPostsByThread | p99 | 154ms | 158ms | 4ms | 2.60
| JobStore.UpdateStatusOptimistically | p99 | 116ms | 119ms | 3ms | 2.58
| JobStore.UpdateStatus | p99 | 117ms | 120ms | 3ms | 2.57
| PostStore.GetPostIdAfterTime | p99 | 81ms | 83ms | 2ms | 2.47
| DraftStore.GetDraftsForUser | p99 | 207ms | 212ms | 5ms | 2.41
| ChannelStore.GetMemberForPost | p99 | 209ms | 214ms | 5ms | 2.39
| UserStore.GetAllProfiles | p99 | 87ms | 89ms | 2ms | 2.29
| UserStore.GetAllProfilesInChannel | p99 | 1.987s | 2.03s | 43ms | 2.16
| PostStore.GetEtag | p99 | 186ms | 190ms | 4ms | 2.15
| PostStore.GetPostsBefore | p99 | 191ms | 195ms | 4ms | 2.10
| SystemStore.GetByName | p99 | 95ms | 97ms | 2ms | 2.09
| AuditStore.Save | p99 | 96ms | 98ms | 2ms | 2.08
| UserStore.GetProfilesByUsernames | p99 | 193ms | 197ms | 4ms | 2.08
| ChannelStore.UpdateSidebarChannelsByPreferences | p99 | 98ms | 100ms | 2ms | 2.04
| ThreadStore.Get | p99 | 159ms | 162ms | 3ms | 1.89
| SessionStore.Get | p99 | 222ms | 226ms | 4ms | 1.80
| PostStore.Save | p99 | 389ms | 396ms | 7ms | 1.80
| ChannelStore.Get | p99 | 224ms | 228ms | 4ms | 1.78
| JobStore.UpdateOptimistically | p99 | 117ms | 119ms | 2ms | 1.72
| ThreadStore.GetThreadUnreadReplyCount | p99 | 183ms | 186ms | 3ms | 1.64
| ChannelStore.GetMembersForUser | p99 | 185ms | 188ms | 3ms | 1.62
| ChannelStore.GetChannels | p99 | 193ms | 196ms | 3ms | 1.56
| ThreadStore.GetThreadsForUser | p99 | 199ms | 202ms | 3ms | 1.51
| DraftStore.Get | p99 | 208ms | 211ms | 3ms | 1.45
| ThreadStore.MaintainMembership | p99 | 230ms | 233ms | 3ms | 1.30
### Store times avg (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| ChannelStore.IsReadOnlyChannel | avg | 12ms | 0s | -12ms | -103.54
| ScheduledPostStore.Get | avg | 16ms | 0s | -16ms | -101.46
| SharedChannelStore.HasChannel | avg | 9ms | 0s | -9ms | -97.39
| ChannelStore.CreateSidebarCategory | avg | 65ms | 23ms | -42ms | -64.57
| CommandWebhookStore.Cleanup | avg | 14ms | 7ms | -7ms | -49.21
| ScheduledPostStore.GetPendingScheduledPosts | avg | 17ms | 9ms | -8ms | -46.44
| TokenStore.Cleanup | avg | 18ms | 11ms | -7ms | -39.87
| UserStore.GetProfilesNotInChannel | avg | 16ms | 10ms | -6ms | -37.11
| RoleStore.ChannelHigherScopedPermissions | avg | 32ms | 22ms | -10ms | -30.81
| TeamStore.SaveMember | avg | 44ms | 39ms | -5ms | -11.41
| ChannelBookmarkStore.Delete | avg | 23ms | 21ms | -2ms | -8.55
| ChannelStore.GetSidebarCategory | avg | 26ms | 24ms | -2ms | -7.79
| PostStore.SetPostReminder | avg | 27ms | 25ms | -2ms | -7.35
| PostStore.SearchPostsForUser | avg | 198ms | 184ms | -14ms | -7.07
| ChannelStore.UpdateSidebarCategories | avg | 103ms | 97ms | -6ms | -5.82
### Store times p99 (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| SharedChannelStore.HasChannel | p99 | 130ms | 0s | -130ms | -100.29
| ChannelStore.IsReadOnlyChannel | p99 | 170ms | 0s | -170ms | -99.71
| ScheduledPostStore.Get | p99 | 25ms | 5ms | -20ms | -80.48
| TokenStore.Cleanup | p99 | 98ms | 25ms | -73ms | -74.49
| ScheduledPostStore.GetPendingScheduledPosts | p99 | 225ms | 84ms | -141ms | -62.60
| ChannelStore.CreateSidebarCategory | p99 | 246ms | 93ms | -153ms | -62.13
| PostPersistentNotificationStore.Get | p99 | 168ms | 70ms | -98ms | -58.49
| RoleStore.ChannelHigherScopedPermissions | p99 | 229ms | 96ms | -133ms | -58.14
| LinkMetadataStore.Save | p99 | 103ms | 47ms | -56ms | -54.61
| PluginStore.List | p99 | 199ms | 95ms | -104ms | -52.26
| CommandWebhookStore.Cleanup | p99 | 49ms | 24ms | -25ms | -51.02
| UserStore.GetProfilesNotInChannel | p99 | 87ms | 48ms | -39ms | -44.57
| UserStore.GetMany | p99 | 169ms | 100ms | -69ms | -40.83
| PostPriorityStore.GetForPost | p99 | 149ms | 92ms | -57ms | -38.20
| UserAccessTokenStore.GetByToken | p99 | 134ms | 107ms | -27ms | -20.08
| TeamStore.SaveMember | p99 | 283ms | 240ms | -43ms | -15.18
| ThreadStore.GetThreadFollowers | p99 | 122ms | 108ms | -14ms | -11.44
| ChannelStore.GetChannelsByUser | p99 | 114ms | 101ms | -13ms | -11.36
| PostAcknowledgementStore.GetForPost | p99 | 95ms | 85ms | -10ms | -10.51
| ChannelStore.GetPinnedPostCount | p99 | 164ms | 152ms | -12ms | -7.31
| FileInfoStore.SetContent | p99 | 229ms | 214ms | -15ms | -6.54
| SessionStore.Remove | p99 | 76ms | 72ms | -4ms | -5.30
| PostStore.SetPostReminder | p99 | 230ms | 221ms | -9ms | -3.91
| FileInfoStore.Save | p99 | 191ms | 184ms | -7ms | -3.66
| JobStore.GetAllByStatus | p99 | 211ms | 204ms | -7ms | -3.31
| ChannelStore.GetAllChannelMembersNotifyPropsForChannel | p99 | 240ms | 236ms | -4ms | -1.67
| ChannelStore.Autocomplete | p99 | 242ms | 238ms | -4ms | -1.65
| TeamStore.GetChannelUnreadsForAllTeams | p99 | 129ms | 127ms | -2ms | -1.55
| PostStore.SearchPostsForUser | p99 | 2.38s | 2.349s | -31ms | -1.30
### API times avg (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| deleteChannelBookmark | avg | 23ms | 88ms | 65ms | 279.62
| updateChannelBookmarkSortOrder | avg | 30ms | 101ms | 71ms | 236.14
| updateReadStateAllThreadsByUser | avg | 7ms | 21ms | 14ms | 206.39
| getChannelMembers | avg | 16ms | 31ms | 15ms | 94.85
| deletePost | avg | 57ms | 102ms | 45ms | 79.00
| login | avg | 127ms | 213ms | 86ms | 67.92
| logout | avg | 88ms | 127ms | 39ms | 44.09
| getTeamStats | avg | 60ms | 84ms | 24ms | 39.89
| createSchedulePost | avg | 16ms | 21ms | 5ms | 31.19
| createUser | avg | 310ms | 400ms | 90ms | 29.06
| unfollowThreadByUser | avg | 59ms | 69ms | 10ms | 16.98
| listCPAValues | avg | 14ms | 16ms | 2ms | 14.63
| getUser | avg | 16ms | 18ms | 2ms | 12.26
| addChannelMember | avg | 486ms | 535ms | 49ms | 10.07
| createChannel | avg | 530ms | 579ms | 49ms | 9.24
| updatePreferences | avg | 43ms | 46ms | 3ms | 6.93
| createDirectChannel | avg | 496ms | 529ms | 33ms | 6.66
| getPublicChannelsForTeam | avg | 30ms | 32ms | 2ms | 6.60
| createGroupChannel | avg | 814ms | 857ms | 43ms | 5.28
| saveReaction | avg | 40ms | 42ms | 2ms | 5.02
| getPostsForChannel | avg | 110ms | 115ms | 5ms | 4.54
| updateReadStateThreadByUser | avg | 137ms | 143ms | 6ms | 4.37
| getFileThumbnail | avg | 61ms | 63ms | 2ms | 3.26
| autocompleteChannelsForTeamForSearch | avg | 66ms | 68ms | 2ms | 3.05
| getFilePreview | avg | 71ms | 73ms | 2ms | 2.82
| createPost | avg | 689ms | 708ms | 19ms | 2.76
| addTeamMember | avg | 1.339s | 1.357s | 18ms | 1.34
### API times p99 (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| getChannelMembers | p99 | 25ms | 244ms | 219ms | 881.29
| deleteChannelBookmark | p99 | 98ms | 485ms | 387ms | 392.89
| updateReadStateAllThreadsByUser | p99 | 23ms | 97ms | 74ms | 314.90
| updateChannelBookmarkSortOrder | p99 | 98ms | 249ms | 151ms | 154.08
| login | p99 | 900ms | 1.95s | 1.05s | 116.71
| createSchedulePost | p99 | 100ms | 216ms | 116ms | 116.29
| getTeamStats | p99 | 212ms | 450ms | 238ms | 112.00
| deletePost | p99 | 440ms | 850ms | 410ms | 93.18
| logout | p99 | 469ms | 860ms | 391ms | 83.30
| createChannelBookmark | p99 | 243ms | 443ms | 200ms | 82.27
| autocompleteChannelsForTeamForSearch | p99 | 356ms | 433ms | 77ms | 21.62
| getPostsForChannel | p99 | 1.429s | 1.628s | 199ms | 13.92
| getTeamMember | p99 | 163ms | 184ms | 21ms | 12.85
| createUser | p99 | 2.061s | 2.304s | 243ms | 11.79
| addChannelMember | p99 | 2.328s | 2.595s | 267ms | 11.47
| listCPAFields | p99 | 165ms | 183ms | 18ms | 10.94
| listCPAValues | p99 | 185ms | 202ms | 17ms | 9.17
| getTeamMembersForUser | p99 | 150ms | 163ms | 13ms | 8.67
| getChannelMembersForUser | p99 | 124ms | 133ms | 9ms | 7.25
| createDirectChannel | p99 | 2.301s | 2.46s | 159ms | 6.91
| unfollowThreadByUser | p99 | 422ms | 450ms | 28ms | 6.64
| saveReaction | p99 | 394ms | 419ms | 25ms | 6.35
| getChannelStats | p99 | 156ms | 165ms | 9ms | 5.77
| getFileThumbnail | p99 | 382ms | 402ms | 20ms | 5.23
| patchPost | p99 | 936ms | 982ms | 46ms | 4.92
| listChannelBookmarksForChannel | p99 | 175ms | 183ms | 8ms | 4.57
| addTeamMember | p99 | 7.972s | 8.323s | 351ms | 4.40
| getTeamsForUser | p99 | 133ms | 138ms | 5ms | 3.77
| getUser | p99 | 241ms | 250ms | 9ms | 3.73
| getFilePreview | p99 | 418ms | 432ms | 14ms | 3.35
| upsertDraft | p99 | 217ms | 224ms | 7ms | 3.23
| updatePreferences | p99 | 421ms | 434ms | 13ms | 3.09
| getUsers | p99 | 233ms | 240ms | 7ms | 3.00
| getChannelMember | p99 | 236ms | 243ms | 7ms | 2.97
| getPostsForChannelAroundLastUnread | p99 | 472ms | 484ms | 12ms | 2.54
| updateReadStateThreadByUser | p99 | 941ms | 964ms | 23ms | 2.44
| getThreadsForUser | p99 | 208ms | 213ms | 5ms | 2.40
| createPost | p99 | 4.329s | 4.43s | 101ms | 2.33
| deleteDraft | p99 | 216ms | 221ms | 5ms | 2.32
| getDrafts | p99 | 218ms | 223ms | 5ms | 2.30
| getChannelsForTeamForUser | p99 | 198ms | 202ms | 4ms | 2.02
| getUsersByNames | p99 | 201ms | 205ms | 4ms | 1.99
| getChannelUnread | p99 | 204ms | 208ms | 4ms | 1.96
| autocompleteUsers | p99 | 368ms | 375ms | 7ms | 1.90
| getTeamScheduledPosts | p99 | 219ms | 223ms | 4ms | 1.83
| createChannel | p99 | 2.313s | 2.35s | 37ms | 1.60
| getChannelMembersForTeamForUser | p99 | 190ms | 193ms | 3ms | 1.58
| createGroupChannel | p99 | 4.247s | 4.306s | 59ms | 1.39
| getClientConfig | p99 | 242ms | 245ms | 3ms | 1.24
| getAllTeams | p99 | 173ms | 175ms | 2ms | 1.16
### API times avg (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| createCategoryForTeamForUser | avg | 69ms | 29ms | -40ms | -57.66
| updateChannelBookmark | avg | 38ms | 24ms | -14ms | -36.36
| followThreadByUser | avg | 67ms | 43ms | -24ms | -35.98
| getChannel | avg | 26ms | 23ms | -3ms | -11.50
| setPostReminder | avg | 78ms | 70ms | -8ms | -10.27
| patchPost | avg | 119ms | 108ms | -11ms | -9.26
| viewChannel | avg | 56ms | 52ms | -4ms | -7.16
| updateCategoriesForTeamForUser | avg | 165ms | 155ms | -10ms | -6.07
| searchPostsInTeam | avg | 220ms | 208ms | -12ms | -5.46
| uploadFileStream | avg | 571ms | 562ms | -9ms | -1.58
### API times p99 (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| createCategoryForTeamForUser | p99 | 246ms | 97ms | -149ms | -60.51
| updateChannelBookmark | p99 | 235ms | 97ms | -138ms | -58.67
| followThreadByUser | p99 | 745ms | 375ms | -370ms | -49.66
| removeUserCustomStatus | p99 | 2.104s | 1.506s | -598ms | -28.42
| updateCategoriesForTeamForUser | p99 | 1.12s | 902ms | -218ms | -19.47
| getChannelsForUser | p99 | 125ms | 113ms | -12ms | -9.61
| getPostThread | p99 | 598ms | 563ms | -35ms | -5.85
| setPostReminder | p99 | 475ms | 451ms | -24ms | -5.05
| getChannel | p99 | 237ms | 231ms | -6ms | -2.53
| viewChannel | p99 | 498ms | 488ms | -10ms | -2.01
| searchAllChannels | p99 | 244ms | 241ms | -3ms | -1.23
### Store times:
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| AuditStore.Save |  Avg| 10ms| 10ms | 0s | 0.000
| |  P99| 96ms| 98ms | 2ms | 2.081
| BotStore.Get |  Avg| 5ms| 6ms | 1ms | 21.742
| |  P99| 24ms| 46ms | 22ms | 91.003
| ChannelBookmarkStore.Delete |  Avg| 23ms| 21ms | -2ms | -8.547
| |  P99| 95ms| 233ms | 138ms | 145.261
| ChannelBookmarkStore.Get |  Avg| 9ms| 11ms | 2ms | 21.236
| |  P99| 92ms| 95ms | 3ms | 3.243
| ChannelBookmarkStore.GetBookmarksForChannelSince |  Avg| 10ms| 10ms | 0s | 0.000
| |  P99| 143ms| 153ms | 10ms | 6.978
| ChannelBookmarkStore.Save |  Avg| 34ms| 33ms | -1ms | -2.972
| |  P99| 235ms| 430ms | 195ms | 83.155
| ChannelBookmarkStore.UpdateSortOrder |  Avg| 21ms| 231ms | 210ms | 979.572
| |  P99| 96ms| 495ms | 399ms | 415.596
| ChannelMemberHistoryStore.LogJoinEvent |  Avg| 7ms| 8ms | 1ms | 13.693
| |  P99| 75ms| 82ms | 7ms | 9.358
| ChannelStore.Autocomplete |  Avg| 52ms| 52ms | 0s | 0.000
| |  P99| 242ms| 238ms | -4ms | -1.654
| ChannelStore.AutocompleteInTeamForSearch |  Avg| 66ms| 68ms | 2ms | 3.052
| |  P99| 356ms| 427ms | 71ms | 19.936
| ChannelStore.CreateDirectChannel |  Avg| 67ms| 81ms | 14ms | 20.752
| |  P99| 466ms| 825ms | 359ms | 76.957
| ChannelStore.CreateInitialSidebarCategories |  Avg| 38ms| 41ms | 3ms | 7.829
| |  P99| 386ms| 411ms | 25ms | 6.482
| ChannelStore.CreateSidebarCategory |  Avg| 65ms| 23ms | -42ms | -64.575
| |  P99| 246ms| 93ms | -153ms | -62.132
| ChannelStore.Get |  Avg| 20ms| 21ms | 1ms | 4.949
| |  P99| 224ms| 228ms | 4ms | 1.783
| ChannelStore.GetAllChannelMembersForUser |  Avg| 13ms| 14ms | 1ms | 7.445
| |  P99| 168ms| 174ms | 6ms | 3.566
| ChannelStore.GetAllChannelMembersNotifyPropsForChannel |  Avg| 22ms| 24ms | 2ms | 9.264
| |  P99| 240ms| 236ms | -4ms | -1.667
| ChannelStore.GetByName |  Avg| 11ms| 11ms | 0s | 0.000
| |  P99| 121ms| 125ms | 4ms | 3.319
| ChannelStore.GetChannelUnread |  Avg| 13ms| 13ms | 0s | 0.000
| |  P99| 185ms| 185ms | 0s | 0.000
| ChannelStore.GetChannels |  Avg| 14ms| 14ms | 0s | 0.000
| |  P99| 193ms| 196ms | 3ms | 1.558
| ChannelStore.GetChannelsByUser |  Avg| 9ms| 9ms | 0s | 0.000
| |  P99| 114ms| 101ms | -13ms | -11.357
| ChannelStore.GetChannelsWithUnreadsAndWithMentions |  Avg| 10ms| 11ms | 1ms | 10.390
| |  P99| 133ms| 162ms | 29ms | 21.799
| ChannelStore.GetFileCount |  Avg| 13ms| 13ms | 0s | 0.000
| |  P99| 163ms| 170ms | 7ms | 4.288
| ChannelStore.GetGuestCount |  Avg| 11ms| 11ms | 0s | 0.000
| |  P99| 141ms| 157ms | 16ms | 11.368
| ChannelStore.GetMember |  Avg| 10ms| 11ms | 1ms | 9.793
| |  P99| 116ms| 130ms | 14ms | 12.076
| ChannelStore.GetMemberCount |  Avg| 36ms| 36ms | 0s | 0.000
| |  P99| 225ms| 226ms | 1ms | 0.444
| ChannelStore.GetMemberForPost |  Avg| 18ms| 19ms | 1ms | 5.489
| |  P99| 209ms| 214ms | 5ms | 2.390
| ChannelStore.GetMemberLastViewedAt |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 93ms| 94ms | 1ms | 1.071
| ChannelStore.GetMembers |  Avg| 15ms| 19ms | 4ms | 26.301
| |  P99| 25ms| 98ms | 73ms | 293.763
| ChannelStore.GetMembersForUser |  Avg| 14ms| 14ms | 0s | 0.000
| |  P99| 185ms| 188ms | 3ms | 1.624
| ChannelStore.GetMembersForUserWithPagination |  Avg| 9ms| 10ms | 1ms | 10.573
| |  P99| 115ms| 124ms | 9ms | 7.840
| ChannelStore.GetPinnedPostCount |  Avg| 10ms| 10ms | 0s | 0.000
| |  P99| 164ms| 152ms | -12ms | -7.308
| ChannelStore.GetPublicChannelsForTeam |  Avg| 29ms| 31ms | 2ms | 7.006
| |  P99| 221ms| 219ms | -2ms | -0.904
| ChannelStore.GetSidebarCategoriesForTeamForUser |  Avg| 15ms| 16ms | 1ms | 6.637
| |  P99| 213ms| 215ms | 2ms | 0.939
| ChannelStore.GetSidebarCategory |  Avg| 26ms| 24ms | -2ms | -7.786
| |  P99| 270ms| 305ms | 35ms | 12.963
| ChannelStore.GetTeamChannels |  Avg| 42ms| 55ms | 13ms | 30.799
| |  P99| 438ms| 450ms | 12ms | 2.743
| ChannelStore.IncrementMentionCount |  Avg| 10ms| 10ms | 0s | 0.000
| |  P99| 115ms| 119ms | 4ms | 3.464
| ChannelStore.IsReadOnlyChannel |  Avg| 12ms| 0s | -12ms | -103.535
| |  P99| 170ms| 0s | -170ms | -99.715
| ChannelStore.Save |  Avg| 50ms| 52ms | 2ms | 3.981
| |  P99| 448ms| 452ms | 4ms | 0.894
| ChannelStore.SaveMember |  Avg| 59ms| 63ms | 4ms | 6.788
| |  P99| 470ms| 490ms | 20ms | 4.255
| ChannelStore.SearchGroupChannels |  Avg| 16ms| 17ms | 1ms | 6.137
| |  P99| 204ms| 202ms | -2ms | -0.982
| ChannelStore.UpdateLastViewedAt |  Avg| 11ms| 12ms | 1ms | 9.213
| |  P99| 97ms| 104ms | 7ms | 7.247
| ChannelStore.UpdateSidebarCategories |  Avg| 103ms| 97ms | -6ms | -5.822
| |  P99| 540ms| 805ms | 265ms | 49.078
| ChannelStore.UpdateSidebarChannelsByPreferences |  Avg| 9ms| 9ms | 0s | 0.000
| |  P99| 98ms| 100ms | 2ms | 2.041
| ClusterDiscoveryStore.SetLastPingAt |  Avg| 18ms| 19ms | 1ms | 5.531
| |  P99| 199ms| 221ms | 22ms | 11.072
| CommandWebhookStore.Cleanup |  Avg| 14ms| 7ms | -7ms | -49.212
| |  P99| 49ms| 24ms | -25ms | -51.021
| DraftStore.Delete |  Avg| 12ms| 14ms | 2ms | 16.422
| |  P99| 126ms| 154ms | 28ms | 22.305
| DraftStore.DeleteDraftsAssociatedWithPost |  Avg| 22ms| 36ms | 14ms | 64.735
| |  P99| 214ms| 239ms | 25ms | 11.682
| DraftStore.Get |  Avg| 16ms| 16ms | 0s | 0.000
| |  P99| 208ms| 211ms | 3ms | 1.445
| DraftStore.GetDraftsForUser |  Avg| 16ms| 16ms | 0s | 0.000
| |  P99| 207ms| 212ms | 5ms | 2.413
| DraftStore.Upsert |  Avg| 15ms| 16ms | 1ms | 6.742
| |  P99| 173ms| 183ms | 10ms | 5.792
| EmojiStore.GetByName |  Avg| 10ms| 10ms | 0s | 0.000
| |  P99| 119ms| 149ms | 30ms | 25.153
| EmojiStore.GetMultipleByName |  Avg| 24ms| 24ms | 0s | 0.000
| |  P99| 224ms| 235ms | 11ms | 4.900
| FileInfoStore.AttachToPost |  Avg| 18ms| 22ms | 4ms | 22.194
| |  P99| 204ms| 228ms | 24ms | 11.750
| FileInfoStore.Get |  Avg| 12ms| 13ms | 1ms | 8.263
| |  P99| 182ms| 189ms | 7ms | 3.839
| FileInfoStore.GetByIds |  Avg| 11ms| 15ms | 4ms | 35.932
| |  P99| 179ms| 217ms | 38ms | 21.209
| FileInfoStore.GetForPost |  Avg| 9ms| 10ms | 1ms | 10.743
| |  P99| 140ms| 139ms | -1ms | -0.715
| FileInfoStore.Save |  Avg| 17ms| 17ms | 0s | 0.000
| |  P99| 191ms| 184ms | -7ms | -3.660
| FileInfoStore.SetContent |  Avg| 24ms| 23ms | -1ms | -4.252
| |  P99| 229ms| 214ms | -15ms | -6.539
| GroupStore.AdminRoleGroupsForSyncableMember |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 89ms| 89ms | 0s | 0.000
| GroupStore.GetByName |  Avg| 8ms| 8ms | 0s | 0.000
| |  P99| 96ms| 100ms | 4ms | 4.158
| GroupStore.GetGroups |  Avg| 10ms| 10ms | 0s | 0.000
| |  P99| 120ms| 140ms | 20ms | 16.666
| JobStore.GetAllByStatus |  Avg| 16ms| 16ms | 0s | 0.000
| |  P99| 211ms| 204ms | -7ms | -3.311
| JobStore.GetCountByStatusAndType |  Avg| 12ms| 19ms | 7ms | 60.665
| |  P99| 204ms| 227ms | 23ms | 11.275
| JobStore.GetNewestJobByStatusesAndType |  Avg| 6ms| 13ms | 7ms | 118.450
| |  P99| 54ms| 219ms | 165ms | 305.556
| JobStore.Save |  Avg| 10ms| 12ms | 2ms | 20.447
| |  P99| 85ms| 91ms | 6ms | 7.059
| JobStore.UpdateOptimistically |  Avg| 10ms| 13ms | 3ms | 28.736
| |  P99| 117ms| 119ms | 2ms | 1.716
| JobStore.UpdateStatus |  Avg| 10ms| 13ms | 3ms | 28.940
| |  P99| 117ms| 120ms | 3ms | 2.574
| JobStore.UpdateStatusOptimistically |  Avg| 13ms| 14ms | 1ms | 7.575
| |  P99| 116ms| 119ms | 3ms | 2.576
| LinkMetadataStore.Get |  Avg| 8ms| 9ms | 1ms | 12.168
| |  P99| 112ms| 137ms | 25ms | 22.360
| LinkMetadataStore.Save |  Avg| 9ms| 8ms | -1ms | -11.673
| |  P99| 103ms| 47ms | -56ms | -54.606
| PluginStore.List |  Avg| 13ms| 14ms | 1ms | 7.593
| |  P99| 199ms| 95ms | -104ms | -52.265
| PostAcknowledgementStore.GetForPost |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 95ms| 85ms | -10ms | -10.510
| PostAcknowledgementStore.GetForPosts |  Avg| 12ms| 13ms | 1ms | 8.175
| |  P99| 207ms| 220ms | 13ms | 6.265
| PostPersistentNotificationStore.DeleteExpired |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 73ms| 73ms | 0s | 0.000
| PostPersistentNotificationStore.Get |  Avg| 9ms| 10ms | 1ms | 10.781
| |  P99| 168ms| 70ms | -98ms | -58.494
| PostPersistentNotificationStore.GetSingle |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 96ms| 99ms | 3ms | 3.131
| PostPriorityStore.GetForPost |  Avg| 8ms| 8ms | 0s | 0.000
| |  P99| 149ms| 92ms | -57ms | -38.199
| PostPriorityStore.GetForPosts |  Avg| 13ms| 14ms | 1ms | 7.594
| |  P99| 212ms| 223ms | 11ms | 5.193
| PostStore.AnalyticsPostCount |  Avg| 542ms| 610ms | 68ms | 12.541
| |  P99| 990ms| 990ms | 0s | 0.000
| PostStore.Delete |  Avg| 37ms| 62ms | 25ms | 67.113
| |  P99| 232ms| 850ms | 618ms | 266.380
| PostStore.Get |  Avg| 29ms| 29ms | 0s | 0.000
| |  P99| 248ms| 248ms | 0s | 0.000
| PostStore.GetEtag |  Avg| 13ms| 13ms | 0s | 0.000
| |  P99| 186ms| 190ms | 4ms | 2.154
| PostStore.GetMaxPostSize |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.GetPostIdAfterTime |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 81ms| 83ms | 2ms | 2.469
| PostStore.GetPostIdBeforeTime |  Avg| 10ms| 10ms | 0s | 0.000
| |  P99| 108ms| 119ms | 11ms | 10.177
| PostStore.GetPostReminderMetadata |  Avg| 10ms| 10ms | 0s | 0.000
| |  P99| 82ms| 192ms | 110ms | 134.144
| PostStore.GetPostReminders |  Avg| 21ms| 23ms | 2ms | 9.570
| |  P99| 201ms| 226ms | 25ms | 12.469
| PostStore.GetPosts |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 88ms| 92ms | 4ms | 4.569
| PostStore.GetPostsAfter |  Avg| 11ms| 11ms | 0s | 0.000
| |  P99| 98ms| 149ms | 51ms | 52.231
| PostStore.GetPostsBefore |  Avg| 15ms| 15ms | 0s | 0.000
| |  P99| 191ms| 195ms | 4ms | 2.098
| PostStore.GetPostsByThread |  Avg| 17ms| 17ms | 0s | 0.000
| |  P99| 154ms| 158ms | 4ms | 2.602
| PostStore.GetPostsSince |  Avg| 27ms| 28ms | 1ms | 3.645
| |  P99| 224ms| 225ms | 1ms | 0.447
| PostStore.GetSingle |  Avg| 8ms| 9ms | 1ms | 12.794
| |  P99| 99ms| 126ms | 27ms | 27.150
| PostStore.InvalidateLastPostTimeCache |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.Save |  Avg| 39ms| 40ms | 1ms | 2.556
| |  P99| 389ms| 396ms | 7ms | 1.800
| PostStore.SearchPostsForUser |  Avg| 198ms| 184ms | -14ms | -7.071
| |  P99| 2.38s| 2.349s | -31ms | -1.303
| PostStore.SetPostReminder |  Avg| 27ms| 25ms | -2ms | -7.345
| |  P99| 230ms| 221ms | -9ms | -3.913
| PostStore.Update |  Avg| 33ms| 32ms | -1ms | -3.040
| |  P99| 232ms| 244ms | 12ms | 5.172
| PreferenceStore.DeleteCategoryAndName |  Avg| 21ms| 28ms | 7ms | 33.663
| |  P99| 214ms| 227ms | 13ms | 6.075
| PreferenceStore.Get |  Avg| 11ms| 13ms | 2ms | 18.106
| |  P99| 165ms| 186ms | 21ms | 12.753
| PreferenceStore.GetAll |  Avg| 10ms| 10ms | 0s | 0.000
| |  P99| 137ms| 136ms | -1ms | -0.728
| PreferenceStore.Save |  Avg| 30ms| 32ms | 2ms | 6.711
| |  P99| 257ms| 296ms | 39ms | 15.173
| ProductNoticesStore.ClearOldNotices |  Avg| 44ms| 45ms | 1ms | 2.287
| |  P99| 99ms| 99ms | 0s | 0.000
| ProductNoticesStore.View |  Avg| 92ms| 100ms | 8ms | 8.730
| |  P99| 800ms| 861ms | 61ms | 7.626
| PropertyFieldStore.SearchPropertyFields |  Avg| 8ms| 9ms | 1ms | 12.278
| |  P99| 100ms| 136ms | 36ms | 36.093
| PropertyValueStore.SearchPropertyValues |  Avg| 13ms| 15ms | 2ms | 15.783
| |  P99| 166ms| 195ms | 29ms | 17.514
| ReactionStore.GetForPost |  Avg| 9ms| 9ms | 0s | 0.000
| |  P99| 97ms| 98ms | 1ms | 1.027
| RoleStore.ChannelHigherScopedPermissions |  Avg| 32ms| 22ms | -10ms | -30.810
| |  P99| 229ms| 96ms | -133ms | -58.143
| RoleStore.GetByNames |  Avg| 28ms| 41ms | 13ms | 46.684
| |  P99| 229ms| 236ms | 7ms | 3.053
| ScheduledPostStore.CreateScheduledPost |  Avg| 12ms| 16ms | 4ms | 33.165
| |  P99| 93ms| 182ms | 89ms | 96.142
| ScheduledPostStore.Get |  Avg| 16ms| 0s | -16ms | -101.459
| |  P99| 25ms| 5ms | -20ms | -80.483
| ScheduledPostStore.GetMaxMessageSize |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ScheduledPostStore.GetPendingScheduledPosts |  Avg| 17ms| 9ms | -8ms | -46.436
| |  P99| 225ms| 84ms | -141ms | -62.597
| ScheduledPostStore.GetScheduledPostsForUser |  Avg| 7ms| 8ms | 1ms | 13.520
| |  P99| 98ms| 99ms | 1ms | 1.024
| ScheduledPostStore.UpdateOldScheduledPosts |  Avg| 11ms| 11ms | 0s | 0.000
| |  P99| 92ms| 95ms | 3ms | 3.270
| SessionStore.Get |  Avg| 19ms| 20ms | 1ms | 5.331
| |  P99| 222ms| 226ms | 4ms | 1.800
| SessionStore.GetLRUSessions |  Avg| 6ms| 7ms | 1ms | 16.252
| |  P99| 85ms| 96ms | 11ms | 12.907
| SessionStore.GetSessionsExpired |  Avg| 14ms| 14ms | 0s | 0.000
| |  P99| 94ms| 97ms | 3ms | 3.208
| SessionStore.GetSessionsWithActiveDeviceIds |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 101ms| 108ms | 7ms | 6.948
| SessionStore.Remove |  Avg| 7ms| 10ms | 3ms | 43.198
| |  P99| 76ms| 72ms | -4ms | -5.298
| SessionStore.Save |  Avg| 14ms| 15ms | 1ms | 7.028
| |  P99| 177ms| 197ms | 20ms | 11.272
| SessionStore.UpdateLastActivityAt |  Avg| 10ms| 11ms | 1ms | 9.925
| |  P99| 93ms| 97ms | 4ms | 4.307
| SharedChannelStore.HasChannel |  Avg| 9ms| 0s | -9ms | -97.394
| |  P99| 130ms| 0s | -130ms | -100.285
| StatusStore.Get |  Avg| 10ms| 10ms | 0s | 0.000
| |  P99| 151ms| 156ms | 5ms | 3.313
| StatusStore.GetByIds |  Avg| 17ms| 18ms | 1ms | 5.850
| |  P99| 207ms| 215ms | 8ms | 3.870
| StatusStore.SaveOrUpdate |  Avg| 13ms| 14ms | 1ms | 7.581
| |  P99| 156ms| 161ms | 5ms | 3.198
| StatusStore.SaveOrUpdateMany |  Avg| 18ms| 19ms | 1ms | 5.687
| |  P99| 205ms| 207ms | 2ms | 0.978
| StatusStore.UpdateExpiredDNDStatuses |  Avg| 11ms| 21ms | 10ms | 90.989
| |  P99| 93ms| 218ms | 125ms | 134.698
| StatusStore.UpdateLastActivityAt |  Avg| 10ms| 10ms | 0s | 0.000
| |  P99| 94ms| 97ms | 3ms | 3.194
| SystemStore.GetByName |  Avg| 8ms| 8ms | 0s | 0.000
| |  P99| 95ms| 97ms | 2ms | 2.095
| TeamStore.Get |  Avg| 7ms| 8ms | 1ms | 13.850
| |  P99| 97ms| 111ms | 14ms | 14.439
| TeamStore.GetActiveMemberCount |  Avg| 58ms| 79ms | 21ms | 36.189
| |  P99| 212ms| 450ms | 238ms | 112.003
| TeamStore.GetAllPage |  Avg| 9ms| 9ms | 0s | 0.000
| |  P99| 125ms| 124ms | -1ms | -0.802
| TeamStore.GetChannelUnreadsForAllTeams |  Avg| 9ms| 9ms | 0s | 0.000
| |  P99| 129ms| 127ms | -2ms | -1.547
| TeamStore.GetMember |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 88ms| 89ms | 1ms | 1.138
| TeamStore.GetTeamsByUserId |  Avg| 9ms| 9ms | 0s | 0.000
| |  P99| 121ms| 125ms | 4ms | 3.300
| TeamStore.GetTeamsForUser |  Avg| 8ms| 9ms | 1ms | 11.904
| |  P99| 106ms| 120ms | 14ms | 13.234
| TeamStore.GetTotalMemberCount |  Avg| 47ms| 72ms | 25ms | 52.835
| |  P99| 99ms| 240ms | 141ms | 142.369
| TeamStore.SaveMember |  Avg| 44ms| 39ms | -5ms | -11.412
| |  P99| 283ms| 240ms | -43ms | -15.183
| ThreadStore.Get |  Avg| 10ms| 10ms | 0s | 0.000
| |  P99| 159ms| 162ms | 3ms | 1.886
| ThreadStore.GetMembershipForUser |  Avg| 10ms| 11ms | 1ms | 9.749
| |  P99| 159ms| 160ms | 1ms | 0.628
| ThreadStore.GetTeamsUnreadForUser |  Avg| 12ms| 12ms | 0s | 0.000
| |  P99| 190ms| 191ms | 1ms | 0.527
| ThreadStore.GetThreadFollowers |  Avg| 8ms| 8ms | 0s | 0.000
| |  P99| 122ms| 108ms | -14ms | -11.440
| ThreadStore.GetThreadForUser |  Avg| 18ms| 19ms | 1ms | 5.569
| |  P99| 215ms| 222ms | 7ms | 3.251
| ThreadStore.GetThreadUnreadReplyCount |  Avg| 20ms| 21ms | 1ms | 4.953
| |  P99| 183ms| 186ms | 3ms | 1.637
| ThreadStore.GetThreadsForUser |  Avg| 16ms| 16ms | 0s | 0.000
| |  P99| 199ms| 202ms | 3ms | 1.507
| ThreadStore.GetTotalThreads |  Avg| 9ms| 9ms | 0s | 0.000
| |  P99| 103ms| 114ms | 11ms | 10.696
| ThreadStore.GetTotalUnreadMentions |  Avg| 8ms| 9ms | 1ms | 12.064
| |  P99| 108ms| 123ms | 15ms | 13.950
| ThreadStore.GetTotalUnreadThreads |  Avg| 9ms| 9ms | 0s | 0.000
| |  P99| 100ms| 119ms | 19ms | 19.052
| ThreadStore.GetTotalUnreadUrgentMentions |  Avg| 9ms| 9ms | 0s | 0.000
| |  P99| 105ms| 117ms | 12ms | 11.421
| ThreadStore.MaintainMembership |  Avg| 21ms| 22ms | 1ms | 4.769
| |  P99| 230ms| 233ms | 3ms | 1.303
| ThreadStore.MarkAllAsReadByChannels |  Avg| 10ms| 12ms | 2ms | 20.225
| |  P99| 97ms| 142ms | 45ms | 46.404
| ThreadStore.MarkAllAsReadByTeam |  Avg| 7ms| 21ms | 14ms | 209.416
| |  P99| 23ms| 97ms | 74ms | 314.899
| ThreadStore.MarkAsRead |  Avg| 10ms| 10ms | 0s | 0.000
| |  P99| 92ms| 95ms | 3ms | 3.262
| ThreadStore.UpdateMembership |  Avg| 9ms| 10ms | 1ms | 10.754
| |  P99| 91ms| 94ms | 3ms | 3.296
| TokenStore.Cleanup |  Avg| 18ms| 11ms | -7ms | -39.871
| |  P99| 98ms| 25ms | -73ms | -74.490
| UserAccessTokenStore.GetByToken |  Avg| 8ms| 9ms | 1ms | 12.146
| |  P99| 134ms| 107ms | -27ms | -20.076
| UserStore.AutocompleteUsersInChannel |  Avg| 75ms| 75ms | 0s | 0.000
| |  P99| 352ms| 366ms | 14ms | 3.980
| UserStore.Count |  Avg| 23ms| 23ms | 0s | 0.000
| |  P99| 181ms| 186ms | 5ms | 2.763
| UserStore.Get |  Avg| 11ms| 12ms | 1ms | 9.300
| |  P99| 152ms| 166ms | 14ms | 9.216
| UserStore.GetAllProfiles |  Avg| 7ms| 8ms | 1ms | 13.631
| |  P99| 87ms| 89ms | 2ms | 2.294
| UserStore.GetAllProfilesInChannel |  Avg| 354ms| 358ms | 4ms | 1.129
| |  P99| 1.987s| 2.03s | 43ms | 2.164
| UserStore.GetByUsername |  Avg| 13ms| 13ms | 0s | 0.000
| |  P99| 138ms| 153ms | 15ms | 10.850
| UserStore.GetForLogin |  Avg| 8ms| 9ms | 1ms | 12.164
| |  P99| 100ms| 126ms | 26ms | 25.887
| UserStore.GetMany |  Avg| 9ms| 12ms | 3ms | 32.268
| |  P99| 169ms| 100ms | -69ms | -40.831
| UserStore.GetProfileByIds |  Avg| 14ms| 14ms | 0s | 0.000
| |  P99| 192ms| 192ms | 0s | 0.000
| UserStore.GetProfilesByUsernames |  Avg| 14ms| 15ms | 1ms | 7.005
| |  P99| 193ms| 197ms | 4ms | 2.075
| UserStore.GetProfilesInChannel |  Avg| 10ms| 16ms | 6ms | 60.955
| |  P99| 84ms| 94ms | 10ms | 11.904
| UserStore.GetProfilesNotInChannel |  Avg| 16ms| 10ms | -6ms | -37.111
| |  P99| 87ms| 48ms | -39ms | -44.572
| UserStore.GetUnreadCount |  Avg| 8ms| 9ms | 1ms | 12.203
| |  P99| 118ms| 128ms | 10ms | 8.444
| UserStore.IsEmpty |  Avg| 3ms| 4ms | 1ms | 28.604
| |  P99| 48ms| 49ms | 1ms | 2.095
| UserStore.Save |  Avg| 95ms| 175ms | 80ms | 83.970
| |  P99| 404ms| 678ms | 274ms | 67.848
| UserStore.Search |  Avg| 50ms| 50ms | 0s | 0.000
| |  P99| 239ms| 240ms | 1ms | 0.418
| UserStore.Update |  Avg| 31ms| 31ms | 0s | 0.000
| |  P99| 233ms| 244ms | 11ms | 4.711
| UserStore.UpdateFailedPasswordAttempts |  Avg| 10ms| 11ms | 1ms | 9.904
| |  P99| 96ms| 99ms | 3ms | 3.137
| UserStore.UpdateLastLogin |  Avg| 9ms| 10ms | 1ms | 11.329
| |  P99| 78ms| 87ms | 9ms | 11.468
| UserStore.UpdateUpdateAt |  Avg| 9ms| 9ms | 0s | 0.000
| |  P99| 80ms| 85ms | 5ms | 6.220
| UserTermsOfServiceStore.GetByUser |  Avg| 8ms| 8ms | 0s | 0.000
| |  P99| 99ms| 110ms | 11ms | 11.090
| WebhookStore.GetOutgoingByTeam |  Avg| 14ms| 15ms | 1ms | 7.014
| |  P99| 191ms| 205ms | 14ms | 7.330
### API times:
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| addChannelMember | Avg| 486ms| 535ms | 49ms | 10.073
| | P99| 2.328s| 2.595s | 267ms | 11.470
| addTeamMember | Avg| 1.339s| 1.357s | 18ms | 1.345
| | P99| 7.972s| 8.323s | 351ms | 4.403
| autocompleteChannelsForTeamForSearch | Avg| 66ms| 68ms | 2ms | 3.047
| | P99| 356ms| 433ms | 77ms | 21.621
| autocompleteUsers | Avg| 70ms| 69ms | -1ms | -1.431
| | P99| 368ms| 375ms | 7ms | 1.905
| createCategoryForTeamForUser | Avg| 69ms| 29ms | -40ms | -57.657
| | P99| 246ms| 97ms | -149ms | -60.507
| createChannel | Avg| 530ms| 579ms | 49ms | 9.241
| | P99| 2.313s| 2.35s | 37ms | 1.600
| createChannelBookmark | Avg| 53ms| 53ms | 0s | 0.000
| | P99| 243ms| 443ms | 200ms | 82.270
| createDirectChannel | Avg| 496ms| 529ms | 33ms | 6.656
| | P99| 2.301s| 2.46s | 159ms | 6.909
| createGroupChannel | Avg| 814ms| 857ms | 43ms | 5.282
| | P99| 4.247s| 4.306s | 59ms | 1.389
| createPost | Avg| 689ms| 708ms | 19ms | 2.756
| | P99| 4.329s| 4.43s | 101ms | 2.333
| createSchedulePost | Avg| 16ms| 21ms | 5ms | 31.191
| | P99| 100ms| 216ms | 116ms | 116.290
| createUser | Avg| 310ms| 400ms | 90ms | 29.064
| | P99| 2.061s| 2.304s | 243ms | 11.791
| deleteChannelBookmark | Avg| 23ms| 88ms | 65ms | 279.622
| | P99| 98ms| 485ms | 387ms | 392.893
| deleteDraft | Avg| 17ms| 18ms | 1ms | 5.984
| | P99| 216ms| 221ms | 5ms | 2.316
| deletePost | Avg| 57ms| 102ms | 45ms | 79.004
| | P99| 440ms| 850ms | 410ms | 93.184
| followThreadByUser | Avg| 67ms| 43ms | -24ms | -35.979
| | P99| 745ms| 375ms | -370ms | -49.663
| getAllTeams | Avg| 10ms| 11ms | 1ms | 9.645
| | P99| 173ms| 175ms | 2ms | 1.158
| getCategoriesForTeamForUser | Avg| 16ms| 17ms | 1ms | 6.246
| | P99| 220ms| 222ms | 2ms | 0.908
| getChannel | Avg| 26ms| 23ms | -3ms | -11.496
| | P99| 237ms| 231ms | -6ms | -2.530
| getChannelMember | Avg| 20ms| 21ms | 1ms | 4.943
| | P99| 236ms| 243ms | 7ms | 2.968
| getChannelMembers | Avg| 16ms| 31ms | 15ms | 94.848
| | P99| 25ms| 244ms | 219ms | 881.288
| getChannelMembersForTeamForUser | Avg| 14ms| 14ms | 0s | 0.000
| | P99| 190ms| 193ms | 3ms | 1.582
| getChannelMembersForUser | Avg| 10ms| 10ms | 0s | 0.000
| | P99| 124ms| 133ms | 9ms | 7.252
| getChannelStats | Avg| 7ms| 7ms | 0s | 0.000
| | P99| 156ms| 165ms | 9ms | 5.770
| getChannelUnread | Avg| 14ms| 15ms | 1ms | 7.060
| | P99| 204ms| 208ms | 4ms | 1.962
| getChannelsForTeamForUser | Avg| 14ms| 15ms | 1ms | 6.903
| | P99| 198ms| 202ms | 4ms | 2.016
| getChannelsForUser | Avg| 9ms| 9ms | 0s | 0.000
| | P99| 125ms| 113ms | -12ms | -9.607
| getClientConfig | Avg| 24ms| 24ms | 0s | 0.000
| | P99| 242ms| 245ms | 3ms | 1.238
| getDrafts | Avg| 17ms| 17ms | 0s | 0.000
| | P99| 218ms| 223ms | 5ms | 2.297
| getFilePreview | Avg| 71ms| 73ms | 2ms | 2.816
| | P99| 418ms| 432ms | 14ms | 3.349
| getFileThumbnail | Avg| 61ms| 63ms | 2ms | 3.258
| | P99| 382ms| 402ms | 20ms | 5.231
| getPostThread | Avg| 66ms| 66ms | 0s | 0.000
| | P99| 598ms| 563ms | -35ms | -5.855
| getPostsForChannel | Avg| 110ms| 115ms | 5ms | 4.545
| | P99| 1.429s| 1.628s | 199ms | 13.924
| getPostsForChannelAroundLastUnread | Avg| 46ms| 46ms | 0s | 0.000
| | P99| 472ms| 484ms | 12ms | 2.544
| getPreferences | Avg| 10ms| 10ms | 0s | 0.000
| | P99| 151ms| 150ms | -1ms | -0.663
| getProfileImage | Avg| 72ms| 72ms | 0s | 0.000
| | P99| 476ms| 476ms | 0s | 0.000
| getPublicChannelsForTeam | Avg| 30ms| 32ms | 2ms | 6.597
| | P99| 228ms| 228ms | 0s | 0.000
| getTeamMember | Avg| 13ms| 13ms | 0s | 0.000
| | P99| 163ms| 184ms | 21ms | 12.851
| getTeamMembersForUser | Avg| 10ms| 10ms | 0s | 0.000
| | P99| 150ms| 163ms | 13ms | 8.674
| getTeamScheduledPosts | Avg| 15ms| 16ms | 1ms | 6.578
| | P99| 219ms| 223ms | 4ms | 1.830
| getTeamStats | Avg| 60ms| 84ms | 24ms | 39.886
| | P99| 212ms| 450ms | 238ms | 112.003
| getTeamsForUser | Avg| 9ms| 9ms | 0s | 0.000
| | P99| 133ms| 138ms | 5ms | 3.765
| getTeamsUnreadForUser | Avg| 17ms| 18ms | 1ms | 5.775
| | P99| 232ms| 234ms | 2ms | 0.863
| getThreadsForUser | Avg| 16ms| 17ms | 1ms | 6.117
| | P99| 208ms| 213ms | 5ms | 2.398
| getUser | Avg| 16ms| 18ms | 2ms | 12.257
| | P99| 241ms| 250ms | 9ms | 3.731
| getUserStatus | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getUserStatusesByIds | Avg| 4ms| 4ms | 0s | 0.000
| | P99| 95ms| 96ms | 1ms | 1.051
| getUsers | Avg| 15ms| 16ms | 1ms | 6.610
| | P99| 233ms| 240ms | 7ms | 3.004
| getUsersByIds | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 58ms| 59ms | 1ms | 1.737
| getUsersByNames | Avg| 15ms| 15ms | 0s | 0.000
| | P99| 201ms| 205ms | 4ms | 1.994
| getWebappPlugins | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| listCPAFields | Avg| 10ms| 11ms | 1ms | 10.111
| | P99| 165ms| 183ms | 18ms | 10.941
| listCPAValues | Avg| 14ms| 16ms | 2ms | 14.629
| | P99| 185ms| 202ms | 17ms | 9.170
| listChannelBookmarksForChannel | Avg| 11ms| 11ms | 0s | 0.000
| | P99| 175ms| 183ms | 8ms | 4.568
| login | Avg| 127ms| 213ms | 86ms | 67.925
| | P99| 900ms| 1.95s | 1.05s | 116.710
| logout | Avg| 88ms| 127ms | 39ms | 44.089
| | P99| 469ms| 860ms | 391ms | 83.302
| patchPost | Avg| 119ms| 108ms | -11ms | -9.261
| | P99| 936ms| 982ms | 46ms | 4.917
| removeUserCustomStatus | Avg| 344ms| 341ms | -3ms | -0.871
| | P99| 2.104s| 1.506s | -598ms | -28.422
| root | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| saveReaction | Avg| 40ms| 42ms | 2ms | 5.020
| | P99| 394ms| 419ms | 25ms | 6.353
| searchAllChannels | Avg| 53ms| 53ms | 0s | 0.000
| | P99| 244ms| 241ms | -3ms | -1.229
| searchGroupChannels | Avg| 17ms| 17ms | 0s | 0.000
| | P99| 208ms| 208ms | 0s | 0.000
| searchPostsInTeam | Avg| 220ms| 208ms | -12ms | -5.460
| | P99| 2.394s| 2.378s | -16ms | -0.668
| searchUsers | Avg| 52ms| 53ms | 1ms | 1.917
| | P99| 241ms| 243ms | 2ms | 0.829
| setPostReminder | Avg| 78ms| 70ms | -8ms | -10.273
| | P99| 475ms| 451ms | -24ms | -5.053
| submitPerformanceReport | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| unfollowThreadByUser | Avg| 59ms| 69ms | 10ms | 16.984
| | P99| 422ms| 450ms | 28ms | 6.637
| updateCategoriesForTeamForUser | Avg| 165ms| 155ms | -10ms | -6.065
| | P99| 1.12s| 902ms | -218ms | -19.467
| updateChannelBookmark | Avg| 38ms| 24ms | -14ms | -36.364
| | P99| 235ms| 97ms | -138ms | -58.669
| updateChannelBookmarkSortOrder | Avg| 30ms| 101ms | 71ms | 236.137
| | P99| 98ms| 249ms | 151ms | 154.078
| updatePreferences | Avg| 43ms| 46ms | 3ms | 6.931
| | P99| 421ms| 434ms | 13ms | 3.091
| updateReadStateAllThreadsByUser | Avg| 7ms| 21ms | 14ms | 206.387
| | P99| 23ms| 97ms | 74ms | 314.899
| updateReadStateThreadByUser | Avg| 137ms| 143ms | 6ms | 4.371
| | P99| 941ms| 964ms | 23ms | 2.444
| updateUserCustomStatus | Avg| 1ms| 0s | -1ms | -140.049
| | P99| 5ms| 5ms | 0s | 0.000
| uploadFileStream | Avg| 571ms| 562ms | -9ms | -1.577
| | P99| 2.29s| 2.283s | -7ms | -0.306
| upsertDraft | Avg| 19ms| 20ms | 1ms | 5.279
| | P99| 217ms| 224ms | 7ms | 3.232
| viewChannel | Avg| 56ms| 52ms | -4ms | -7.157
| | P99| 498ms| 488ms | -10ms | -2.007
